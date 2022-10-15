The failure-inducing input (the code of the test):

	@Test 
	public void testReverseInPlace() {
    int[] input1 = { 1,2,3,4,5 };
    ArrayExamples.reverseInPlace(input1);
    assertArrayEquals(new int[]{ 5,4,3,2,1 }, input1);
	}
The symptom (the failing test output):

    The expected output was 1,2,3,4,5 but the acual was 5,4,3,4,5.
The bug (the code fix needed):
    
    static void reverseInPlace(int[] arr) {
    for(int i = 0; i < arr.length/2; i += 1) {
      int temp = arr[i];
      arr[i] = arr[arr.length - i - 1];
      arr[arr.length - i - 1] = temp;
    }

Then, explain the connection between the symptom and the bug. Why does the bug cause that particular symptom for that particular input? 

The symptom occurs because this method only reverses the values on the right side of an array list and simply replace them on the left side, but does not swap the values on the left side. My input is  {1,2,3,4,5} the reuslt is {5,4,3,4,5} instead of {5,4,3,2,1}

