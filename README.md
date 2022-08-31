# UC Davis Preliminary Solutions
This is the **temporary** home of the UC Davis preliminary exam solutions, the student-built, comprehensive collection of solutions to past preliminary exams.
These solutions will soon be migrated to the Galois Group website.

## Building the books
Simply compile the `main.tex` file in any of the exam subdirectories using your favorite LaTeX compiler.
That's it!
The project utilizes the `subfile` package to separate each problem into its own easy-to-manage file.
Tested with lualatex and pdflatex.

## Contributing solutions
Infinite thanks to everyone who is contributing to this massive project.
If you have solutions to problems, there are 2 ways to contribute:
1. **Email your solutions** to Colby.
TeX files are prefered, although pdfs or legible handwritten notes can be transcribed.
2. **Fork and open a pull request** for this project.
Read about [how to fork](https://docs.github.com/en/get-started/quickstart/fork-a-repo).
Please follow the style guide.

## I found a mistake. How do I get it fixed?
If you think you found a mistake in a solution, there are 3 ways to report it:
1. **Open an issue.** 
Read about [how to open issues](https://docs.github.com/en/issues/tracking-your-work-with-issues/creating-an-issue).
2. **Email Colby.** 
Please be specific in what you think the problem is, and if you have a proposed solution, please write it up.
If I do not have the expertise to understand the problem, I will do my best to translate your email into a github issue for others to see.
3. **Fix the problem yourself.**
Write up your solution and open a pull request.
In your commit and pull request messages, please be specific about what the problem was.

## How can I help?
You can help this project in a few ways.
1. If you have solutions or are writing any, please share them using one of the above methods.
2. Look through the open issues (if there are any) and see if you can fix any incorrect solutions.
3. If you have old real life preliminary exams, please send me scans if you feel comfortable doing so.
They will be anonymized.
If you have a scoring breakdown, please send it to me as well.

## Style Guide
Please write your proofs in your voice; we will collect multiple solutions for people to see a range of acceptable responses.
Otherwise, please follow these style guidelines:
1. In your TeX file, please use *only one sentence* per line in the `.tex` file.
This will greatly improve the readability of proposed changes in git.
Place inline math inline, and place display style math in its own line.
2. Follow the existing file structure and naming guidelines.
Feel free to copy+paste other solution files as a template.
3. In your solution file, please begin with this line:
`%! TeX root = ../analysis-main.tex`
(or similar for other exams).
This will help TeX compilers understand the structure of the project.
4. Follow [good git commit message hygine](https://commit.style).
