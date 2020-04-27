We have experimented on thirty java programs to validate our approach SMUP. There are eight sub-folders are there for four scenarios(original,JPCT,JEXNCT and PBCT) containing program type and its respective test case file.

1. http://rers-challenge.org/
2. https://github.com/osl/jCUTE/tree/master/src/tests
3. http://www.programmingsimplified.com/java-sthe proposedce-codes

SMUP execution Steps:

Step1. Original programs are used to generate the transformed version of the input java program using source code transformation techniques (JPCT,JEXNCT and PBCT).

Step2. These java files (original,JPCT transformed,JEXNCT transformed and PBCT transformed) are used to generate test cases using jCUTE.

Step3.  The following link provides details about how to install and use jCUTE. 
	https://github.com/osl/jcute

Step4. Once the test case file is generated, we can get the MC/DC percentage using the JMA tool. The JMA too requires the original java file and the test cases generated from transformed version to get achieve higher MC/DC percentage.