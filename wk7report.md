# Topic: CLDQ
For this week's lab report, I'll be going through the steps of the lab competition. All key presses are done on VSCode and work on Mac. Read *Notes* if you are doing this for the first time. The keys pressed below were used by me to comfortably, efficiently, and quickly work with the command line after having already done the task before. Assume spaces within angle brackets have the form `<space>`.
  
List of special key presses in order of appearance: **(ALL OTHER KEY PRESSES ARE LETTERS/SPACES ON THE KEYBOARD)**
1. `<up>` arrow key to navigate upwards
2. `<enter>` enter/return key to execute code
3. `<ctrl+r>` search command history
4. `<cmd+v>` paste copied item
5. `<tab>` tab key to autocomplete/autofill possible paths
6. `<right>` arrow key to navigate to the right
7. `<backspace>` backspace/delete key to delete a character before the cursor
8. `<ctrl+o>` used in nano to save a file
9. `<ctrl+x>` used in nano to exit a file
  

## Step 1: Setup
* Generate SSH Keys for ieng6 and GitHub. Instructions can be found [here](https://ucsd-cse15l-w23.github.io/week/week7/).
* Fork a new lab 7 repository which can be found [here](https://github.com/ucsd-cse15l-w23/lab7).
* Start the timer!

## Step 2: Log into your ieng6
* Keys pressed: `<up><enter>` 

*Notes: `ssh cs15lwi23xxx@ieng6.ucsd.edu` was 1 up in my search history. Type out `<ssh cs15lwi23xxx@ieng6.ucsd.edu>` if it isn't in your history.*

![image](https://raw.githubusercontent.com/cheahfulnic/lab7/main/wk7-ss/week7-1.png)
 
## Step 3: Clone your lab 7 repository from GitHub
* On your lab 7 repository page, click the '<> Code' button, click on the SSH tab, and then click on the copy button on the right of the Git URL.

![image](https://raw.githubusercontent.com/cheahfulnic/lab7/main/wk7-ss/week7-2.png)
* Keys pressed: `<ctrl+r><cl><enter>` 

*Notes: Type out `<git clone ><cmd+v>` if it isn't in your history.*

![image](https://raw.githubusercontent.com/cheahfulnic/lab7/main/wk7-ss/week7-3.png)
  
## Step 4: Run the tests to demonstrate they fail
* Keys pressed: `<cd l><tab><enter><ctrl+r><javac><enter><ctrl+r><java ><enter>`

*Notes: Replace `<ctrl+r><javac>` and `<ctrl+r><java >` by typing out/copying+pasting `javac -cp .:lib/hamcrest-core-1.3.jar:lib/junit-4.13.2.jar *.java` and `java -cp .:lib/hamcrest-core-1.3.jar:lib/junit-4.13.2.jar org.junit.runner.JUnitCore ListExamplesTests` respectively if they aren't in your history.*

![image](https://raw.githubusercontent.com/cheahfulnic/lab7/main/wk7-ss/week7-4.png)
  
## Step 5: Edit the code and fix the test
* Keys pressed: `<ctrl+r><na><enter> scroll all the way down <up> x7 <right> x12 <backspace><2><ctrl+o><enter><ctrl+x>`

*Notes: Replace `<ctrl+r><na>` by typing out `<nano L><tab><.j><tab>` if it isn't in your history.*

![image](https://raw.githubusercontent.com/cheahfulnic/lab7/main/wk7-ss/week7-5.png)
![image](https://raw.githubusercontent.com/cheahfulnic/lab7/main/wk7-ss/week7-6.png)

## Step 6: Run the tests to demonstrate they succeed
* Keys pressed: `<up><up><up><enter><up><up><up><enter>`

*Notes: javac and java commands were 3 ups in my search history respectively.*

![image](https://raw.githubusercontent.com/cheahfulnic/lab7/main/wk7-ss/week7-7.png)

## Step 7: Add, commit and push
* Keys pressed: `<ctrl+r><ad><enter><ctrl+r><comm><enter><ctrl+r><pu><enter>`

*Notes: Replace `<ctrl+r><ad>` by typing `<git add L><tab><.j><tab>`. Replace `<ctrl+r><comm>` by typing `<git commit -m "Fixed">`. Replace `<ctrl+r><pu>` by typing `<git push origin main>`.*

![image](https://raw.githubusercontent.com/cheahfulnic/lab7/main/wk7-ss/week7-8.png)

