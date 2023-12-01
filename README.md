# Command-Line Banking Application

![Screenshot](banking-application.gif?raw=true)

![Badge](badges/badge-1.svg?raw=true&sanitize=true)&emsp;![Badge](badges/badge-2.svg?raw=true&sanitize=true)&emsp;![Badge](badges/badge-3.svg?raw=true&sanitize=true)

> **Note:** To view the code in the GitHub repository with proper formatting, make sure to change the tab size from the default **8** to **4**. You can adjust this setting in `GitHub > Settings > Appearance > Tab Size Preference`.

## Running a C Program on Linux with GCC
C programs are compiled using the GNU Compiler (GCC) and executed in the Linux terminal. Follow the steps below to run the program: 

![Screenshot](run-the-program-1.png?raw=true)

- [x] Install dependencies \
***How to install gcc on ubuntu 18.04...***

**Use a text editor to write a C program** \
Open the C program file (`runtheprogram.c`) in your preferred text editor, for example, using:
```bash
gedit runtheprogram.c
```
**Check a C program**
```bash
cat runtheprogram.c
```
**Compile a C program**
> **Note:** This command will invoke the GNU Compiler (GCC) to compile the file `runtheprogram.c` and output (-o) the result to an executable called `experiment`.

```bash
gcc runtheprogram.c -o experiment
```
**Run the C Program (Machine Code)**
```bash
./experiment
```

![Screenshot](run-the-program-2.png?raw=true)

## License
Please refer to the [LICENSE](LICENSE) file for information on the license terms and any associated rights and limitations (MIT).
