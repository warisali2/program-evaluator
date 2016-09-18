# program-evaluator
A simple program evaluator. Useful for practicing for Competitive Programming Competitions

## Introduction
While practicing for Programming Competitions, Have you ever been in a situation where you had to enter inputs again and again for every change you made in your code? It really gets tiring, doesn't it? This is where **pe** helps you! It automates the testing of program by saving you from the trouble of manually inputing data.

## Syntax
```
pe PROGRAM_FILE INPUT_FILE OUTPUT_FILE
```
For help, use: `pe -h`

## Example
```
pe main.exe input.txt output.txt
```
![example-image-01.png](https://github.com/warisali2/program-evaluator/blob/readme-edits/example-image-01.png)

```
pe myprogram mycode/input mycode/output
```
![example-image-02.png](https://github.com/warisali2/program-evaluator/blob/readme-edits/example-image-02.png)

## Installation

### For Linux
1. Download **pe** script.
2. Copy the file to `\bin` or `\usr\bin`.
3. Change the Permission to make it executable.
    1. `cd` to the directory where **pe** is located.
    2. Use `chmod u+x pe` to make it executable.

### For Windows
1. For Windows 10, install [Linux Bash Shell](http://www.howtogeek.com/249966/how-to-install-and-use-the-linux-bash-shell-on-windows-10/). For earlier versions of Windows, install [Cygwin](https://www.cygwin.com/).
2. Download **pe** script.
3. Change the Permission to make it executable.
    1. `cd` to the directory where **pe** is located.
    2. Use `chmod u+x pe` to make it executable.

## Features
- [x] Highlights Correct and Incorrect output with Green and Red colors respectively.
- [ ] Show incorrect output only.
- [ ] Randomly generate input using user-defined templates.
