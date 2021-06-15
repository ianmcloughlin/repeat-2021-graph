# Autumn Project 2021: Graph Theory

**Due: last commit on or before 20<sup>th</sup> August 2021**


These are the instructions for the Autumn project in 2021.
This project will be worth 100% of your marks for this module, unless otherwise agreed in advance with the lecturer.
Your whole submission should be in the form of a single GitHub repository.
The commit history of the repository should reflect the effort you put into it.
Your last pushed commit before the deadline will form your submission.
You should immediately create this repository and submit its URL using the following form.


[Click here to submit your GitHub repository URL](https://forms.office.com/r/whWTJsDuz7)



You should make regular, appropriate commits to your repository and push these to GitHub.
If you set your repository to private, make sure to add `ianmcloughlin` as a collaborator.
Please also read the **[Using git for assessments](https://github.com/ianmcloughlin/using-git-for-assessments/raw/master/using-git-for-assessments.pdf)** document which applies to this project.
As always, you must also follow [the code of student conduct and the policy on plagiarism](https://www.gmit.ie/general/quality-assurance-framework).


## What to do

There are two parts to this project, as below.

#### Part 1

Write a program in Python 3 that takes a regular expression and a file as command line arguments, and outputs the number of matches for the regular expression within the file.
Yuo may limit yourself to regular languages, with the concatenation operator `.`, the or operator `|`, and the Kleene star `*`.
The program should work as follows:

```bash
$ python3 rescript.py a.b input.txt
3
```
where `input.txt` contains the following text:

```text
fab cab
dab cat
```

The following are the requirements of the program.

1. The input file should be taken as a command line argument, without any flags or other arguments being necessary.
2. The regular expression should be taken as a command line argument, without any flags or other arguments being necessary.
3. Your program should accept the `--help` and `-h` flags. When these are specified on the command line, the program should simply output how to use the program.
4. Your program should not depend on any external packages or libraries.
5. Your program should not depend on the `re` module in the Python standard library, but any other module from the standard library can be used. 
6. Your README should detail the use of your program.

#### Part 2

Answer the following three questions in your README.
Each answer should be roughly 500 words in length.
You should make use of referencing to demonstrate that your answers are backed up by reliable sources.

1. Explain the difference between regular expressions in infix notation and those in postfix notation.
2. Explain how Thompson's construction for regular expressions works.
3. Explain what is meant by the term *irregular language* in the context of regular expressions.


## Enhancements

To enhance your submission, and potentially enhance your mark, you might consider implementing some or all of the following features.

1. Allow multiple input files to be specified as command line arguments, with your program outputting the number of matches in order.
2. Enable your program to take input from `stdin` rather than an input file.
3. Allow the user to use the `--verbose` command line flag to see the matches along with the total number.


## Marking scheme

The following marking scheme will be used to mark your submission out of 100%.
The examiners' overall impression of your submission may influence individual marks.
It is important that your submission provides direct evidence of each of the items listed in each category.
For instance, your commit history should demonstrate and provide evidence that you had a pragmatic attitude to completing the assessment.
Likewise, your submission should have references in it to demonstrate that you considered the literature and the work of others.
  

| Weight | Category | Description |
|---|---|---|
|25% | Research | Evidence of research performed on topic; submission based on referenced literature, particularly academic literature; evidence of understanding of the documentation for any software or libraries used. |
|25% | Development | Environment can be set up as described; code works without tweaking and as described; code is efficient, clean, and clear; evidence of consideration of standards and conventions appropriate to code of this kind. |
|25% | Consistency | Evidence of planning and project management; pragmatic attitude to work as evidenced by well-considered commit history; commits are of a reasonable size; consideration of how commit history will be perceived by others. |
|25% | Documentation | Clear documentation of how to create an environment in which any code will run, how to prepare the code for running, how to run the code including setting any options or flags, and what to expect upon running the code. Concise descriptions of code in comments and README. |