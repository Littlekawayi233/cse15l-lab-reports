# Lab report 3

## less plos/pmed.0010029.txt
```
There is a much-quoted saying, attributed to the epidemiologist Geoffrey Rose: “A large
        number of people exposed to a small risk may generate many more cases than a small number
        exposed to a very high risk.” This is true for many individual risk factors such as salt
        intake (linked to high blood pressure and cardiovascular disease) and speeding on the
        highway (linked to injuries and accidents). Does it apply to many other global health
        risks? The study by Anthony Rodgers and colleagues suggests that it does.
        To develop effective health policies, one must understand the existing health risks and
        disease burdens. On a worldwide scale, this is a tough challenge. The Global Burden of
        Disease Database, maintained by the World Health Organization (WHO), collects data from
        countries around the world on risk factors such as tobacco, malnutrition, childhood abuse,
        unsafe sex, childbirth, and cholesterol levels, as well as on disease burdens, for example
        depression, blindness, and diarrhea. A large group of scientists from all over the world
        has developed a framework to analyze these data. To compare different risks or burdens,
        they calculate disability-adjusted life-years, or DALYs—the number of healthy life years
        lost because of a particular disease or risk factor.
        Rodgers and colleagues used data from the WHO database for 26 risk factors and from 14
        epidemiological subregions of the world to calculate the proportion of
        risk-factor-attributable disease burden in different population subgroups defined by age,
        sex, and exposure level. For being underweight in childhood, for example—the leading risk
        factor for global loss of healthy life—they found that only 35% of the disease burden
        occurred in severely underweight children, the rest occurred in those only moderately
        underweight. The relative risks for the moderately underweight are much lower, but the
        number of children in that category is so large that the total attributable burden amounted
        to almost two-thirds of the total global burden of disease for that risk factor.
        The analysis confirms—and extends to a global level—previous research showing that many
        major health risks are important across the range of exposure levels, not just among
        individuals exposed to high levels of risk. It also points to risk factors that are
        particularly prevalent among specific populations and age groups, and for which highly
        targeted interventions could be effective.
        Despite numerous caveats and limitations of studies like this one, such analyses are
        essential aids in guiding the distribution of limited funds to lower the burden of life
        years lost to premature death and disability.
```
The less command displays the contentes of a file. For example, I printed out the contents of pmed.0010029.txt.

### 1.
```
zhaoyudou@Zhaoyus-MacBook-Air plos % cat pmed.0010029.txt

  
    
      
        
        There is a much-quoted saying, attributed to the epidemiologist Geoffrey Rose: “A large
        number of people exposed to a small risk may generate many more cases than a small number
        exposed to a very high risk.” This is true for many individual risk factors such as salt
        intake (linked to high blood pressure and cardiovascular disease) and speeding on the
        highway (linked to injuries and accidents). Does it apply to many other global health
        risks? The study by Anthony Rodgers and colleagues suggests that it does.
        To develop effective health policies, one must understand the existing health risks and
        disease burdens. On a worldwide scale, this is a tough challenge. The Global Burden of
        Disease Database, maintained by the World Health Organization (WHO), collects data from
        countries around the world on risk factors such as tobacco, malnutrition, childhood abuse,
        unsafe sex, childbirth, and cholesterol levels, as well as on disease burdens, for example
        depression, blindness, and diarrhea. A large group of scientists from all over the world
        has developed a framework to analyze these data. To compare different risks or burdens,
        they calculate disability-adjusted life-years, or DALYs—the number of healthy life years
        lost because of a particular disease or risk factor.
        Rodgers and colleagues used data from the WHO database for 26 risk factors and from 14
        epidemiological subregions of the world to calculate the proportion of
        risk-factor-attributable disease burden in different population subgroups defined by age,
        sex, and exposure level. For being underweight in childhood, for example—the leading risk
        factor for global loss of healthy life—they found that only 35% of the disease burden
        occurred in severely underweight children, the rest occurred in those only moderately
        underweight. The relative risks for the moderately underweight are much lower, but the
        number of children in that category is so large that the total attributable burden amounted
        to almost two-thirds of the total global burden of disease for that risk factor.
        The analysis confirms—and extends to a global level—previous research showing that many
        major health risks are important across the range of exposure levels, not just among
        individuals exposed to high levels of risk. It also points to risk factors that are
        particularly prevalent among specific populations and age groups, and for which highly
        targeted interventions could be effective.
        Despite numerous caveats and limitations of studies like this one, such analyses are
        essential aids in guiding the distribution of limited funds to lower the burden of life
        years lost to premature death and disability.
```
The cat command also displays the contents of a file, therefore we can use it to substitute the less method in this case.

### 2.
```

 zhaoyudou@Zhaoyus-MacBook-Air plos % wc pmed.0010029.txt      
      40     412    2963 pmed.0010029.txt
zhaoyudou@Zhaoyus-MacBook-Air plos % tail -40 pmed.0010029.txt

  
    
      
        
        There is a much-quoted saying, attributed to the epidemiologist Geoffrey Rose: “A large
        number of people exposed to a small risk may generate many more cases than a small number
        exposed to a very high risk.” This is true for many individual risk factors such as salt
        intake (linked to high blood pressure and cardiovascular disease) and speeding on the
        highway (linked to injuries and accidents). Does it apply to many other global health
        risks? The study by Anthony Rodgers and colleagues suggests that it does.
        To develop effective health policies, one must understand the existing health risks and
        disease burdens. On a worldwide scale, this is a tough challenge. The Global Burden of
        Disease Database, maintained by the World Health Organization (WHO), collects data from
        countries around the world on risk factors such as tobacco, malnutrition, childhood abuse,
        unsafe sex, childbirth, and cholesterol levels, as well as on disease burdens, for example
        depression, blindness, and diarrhea. A large group of scientists from all over the world
        has developed a framework to analyze these data. To compare different risks or burdens,
        they calculate disability-adjusted life-years, or DALYs—the number of healthy life years
        lost because of a particular disease or risk factor.
        Rodgers and colleagues used data from the WHO database for 26 risk factors and from 14
        epidemiological subregions of the world to calculate the proportion of
        risk-factor-attributable disease burden in different population subgroups defined by age,
        sex, and exposure level. For being underweight in childhood, for example—the leading risk
        factor for global loss of healthy life—they found that only 35% of the disease burden
        occurred in severely underweight children, the rest occurred in those only moderately
        underweight. The relative risks for the moderately underweight are much lower, but the
        number of children in that category is so large that the total attributable burden amounted
        to almost two-thirds of the total global burden of disease for that risk factor.
        The analysis confirms—and extends to a global level—previous research showing that many
        major health risks are important across the range of exposure levels, not just among
        individuals exposed to high levels of risk. It also points to risk factors that are
        particularly prevalent among specific populations and age groups, and for which highly
        targeted interventions could be effective.
        Despite numerous caveats and limitations of studies like this one, such analyses are
        essential aids in guiding the distribution of limited funds to lower the burden of life
        years lost to premature death and disability.
```
        The tail command displays the last ten lines of a file by default. If we want to show the exact line of a file from the last, we could add -n to this command. For example, I use wc command to know that this file has a total of 40 lines, so the tail -40 commmand would display all the contents. It's useful because we can modify the number to show the contents that we would like to see.
        
### 3.
```
        head -40 pmed.0010029.txt
    
        There is a much-quoted saying, attributed to the epidemiologist Geoffrey Rose: “A large
        number of people exposed to a small risk may generate many more cases than a small number
        exposed to a very high risk.” This is true for many individual risk factors such as salt
        intake (linked to high blood pressure and cardiovascular disease) and speeding on the
        highway (linked to injuries and accidents). Does it apply to many other global health
        risks? The study by Anthony Rodgers and colleagues suggests that it does.
        To develop effective health policies, one must understand the existing health risks and
        disease burdens. On a worldwide scale, this is a tough challenge. The Global Burden of
        Disease Database, maintained by the World Health Organization (WHO), collects data from
        countries around the world on risk factors such as tobacco, malnutrition, childhood abuse,
        unsafe sex, childbirth, and cholesterol levels, as well as on disease burdens, for example
        depression, blindness, and diarrhea. A large group of scientists from all over the world
        has developed a framework to analyze these data. To compare different risks or burdens,
        they calculate disability-adjusted life-years, or DALYs—the number of healthy life years
        lost because of a particular disease or risk factor.
        Rodgers and colleagues used data from the WHO database for 26 risk factors and from 14
        epidemiological subregions of the world to calculate the proportion of
        risk-factor-attributable disease burden in different population subgroups defined by age,
        sex, and exposure level. For being underweight in childhood, for example—the leading risk
        factor for global loss of healthy life—they found that only 35% of the disease burden
        occurred in severely underweight children, the rest occurred in those only moderately
        underweight. The relative risks for the moderately underweight are much lower, but the
        number of children in that category is so large that the total attributable burden amounted
        to almost two-thirds of the total global burden of disease for that risk factor.
        The analysis confirms—and extends to a global level—previous research showing that many
        major health risks are important across the range of exposure levels, not just among
        individuals exposed to high levels of risk. It also points to risk factors that are
        particularly prevalent among specific populations and age groups, and for which highly
        targeted interventions could be effective.
        Despite numerous caveats and limitations of studies like this one, such analyses are
        essential aids in guiding the distribution of limited funds to lower the burden of life
        years lost to premature death and disability.
```
The head command displays the first 10 lines by default. Just as the tail command, we can modify it to show all the contents by passing -40. It's useful because we can modify the number to show the contents that we would like to see.

## grep 
```
zhaoyudou@Zhaoyus-MacBook-Air plos % grep "global " pmed.0010029.txt   
        highway (linked to injuries and accidents). Does it apply to many other global health
        factor for global loss of healthy life—they found that only 35% of the disease burden
        to almost two-thirds of the total global burden of disease for that risk factor.
        The analysis confirms—and extends to a global level—previous research showing that many

```
The grep command stands for global regular expression print, it searches for a string in a file and prints the lines that match it.

### 4.
```
zhaoyudou@Zhaoyus-MacBook-Air plos % grep -n "global" pmed.0010029.txt
10:        highway (linked to injuries and accidents). Does it apply to many other global health
25:        factor for global loss of healthy life—they found that only 35% of the disease burden
29:        to almost two-thirds of the total global burden of disease for that risk factor.
30:        The analysis confirms—and extends to a global level—previous research showing that many
```
The grep -n command not only gives us the same result as grep but it also tells us the number of line which contains the string. It's useful as it helps us identify the string where it belongs to.

### 5.
```
zhaoyudou@Zhaoyus-MacBook-Air plos % grep -i "global " pmed.0010029.txt
        highway (linked to injuries and accidents). Does it apply to many other global health
        disease burdens. On a worldwide scale, this is a tough challenge. The Global Burden of
        factor for global loss of healthy life—they found that only 35% of the disease burden
        to almost two-thirds of the total global burden of disease for that risk factor.
        The analysis confirms—and extends to a global level—previous research showing that many
```
The grep -i command perform case insensitive matching, since by default grep is case sensitive. It's useful when we want to search all the string regardless of case.

### 6.
```
zhaoyudou@Zhaoyus-MacBook-Air plos % grep -c "global " pmed.0010029.txt
4
```
The grep -i command counts how many times the word appears in this file. It's useful when we are doing the search in a large file and would like to how many times a string appears in the file.

### 7.
```
zhaoyudou@Zhaoyus-Air technical % find plos -empty     
plos/journal.pbio.0020116.txt
```
The find plos -empty command find all empty folders and files in the plos directory, which can help us know how many files that are not empty in the directory.

### 8.
```
zhaoyudou@Zhaoyus-Air technical % find plos -name journal.pbio.0020112.txt
plos/journal.pbio.0020112.txt
```
The find plos -name journal.pbio.0020112.txt searchs for the file in directory. It's useful when we want to know if a file exists in the directory.

### 9.
```
zhaoyudou@Zhaoyus-Air technical % find . -type d
.
./government
./government/About_LSC
./government/Env_Prot_Agen
./government/Alcohol_Problems
./government/Gen_Account_Office
./government/Post_Rate_Comm
./government/Media
./plos
./biomed
./911report
```
 The find . -type d command finds all the directory in the technical. "d" represents directory. We can also modify "d" to "f" to represent file “l” for the symbolic link, and “s” for sockets. It's useful when we want to find out know what subdirectories are in the current working directory.