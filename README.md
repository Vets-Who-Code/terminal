# **Terminal Navigation Assignment**

## **Objective**
This assignment will help you practice **essential terminal navigation commands** used in Linux/macOS.

By the end of this assignment, you should be able to:
- Navigate directories using the terminal.
- Use commands like `pwd`, `ls`, `cd`, `find`, `cat`, and `grep`.
- Locate and read files using command-line tools.

---

## **Assignment Instructions**

### **Step 1: Set Up Your Environment**
1. Open the **GitHub Codespace** or **your terminal** if working locally.
2. Verify that your working directory contains the following structure:

/terminal-navigation-assignment
│── practice-directory/
│   ├── folder1/
│   │   ├── fileA.txt
│   ├── folder2/
│   │   ├── fileB.txt
│   ├── fileC.txt

---

### **Step 2: Complete the Following Tasks**
Use terminal commands to complete each task below.

1. **Print your current working directory (absolute path).**
```sh
pwd
```
	2.	List all files and directories inside practice-directory.
```
ls practice-directory
```

	3.	Change into folder1 and verify you are inside it.
```
cd practice-directory/folder1
pwd
```

	4.	Display the contents of fileA.txt.
```
cat fileA.txt
```

	5.	Return to the terminal-navigation-assignment root directory in a single command.
```
cd ../../
```

	6.	Find all .txt files inside practice-directory.
```
find practice-directory -name "*.txt"
```

	7.	Search for the word “Navigation” inside fileC.txt.
```
grep "Navigation" practice-directory/fileC.txt
```


⸻

Step 3: Submit Your Work
	1.	Run the test script to verify your work:
```
bash test_navigation.sh
```

	2.	If all tests pass, commit and push your work:

```
git add .
git commit -m "Completed Terminal Navigation Assignment"
git push
```

	3.	Your work will be automatically graded using GitHub Actions.

⸻

Evaluation Criteria

Your assignment will be automatically graded based on:
✅ Correct execution of each command.
✅ Accurate directory navigation.
✅ Successful file searching and reading.
✅ Passing all tests in test_navigation.sh.

Good luck and happy navigating! 🚀
