# rs-1-4-dog-years

## Git Config for Local Git
```
git config user.name "user"
git config user.email "email"
```

## Compiling and Running Java Programs
To compile a Java file, run the following command in the terminal.  Substitute your actual file name for the `FileName`.
```
javac FileName.java
```

Alternatively, you can compile every Java file using the asterisk (*).  Be careful about doing this for larger projects whose files rely on each other though.
```
javac *.java
```
The star means to compile every file that is a Java file type.

Run your code by running
```
java FileName
```

# Instructions  

In this coding challenge, you will calculate your age, and your pet’s age from your birthdates, and your pet’s age in dog years. In the code, create a `Scanner` and prompt the user for the current year, the year they were born, the year their dog or cat was born (if they don’t have one, then they should make one up!) in the variables below. Then write formulas in assignment statements to calculate how old they are, how old their dog or cat is, and how old the dog / cat is in dog years which is 7 times a human year. Finally, print it all out.