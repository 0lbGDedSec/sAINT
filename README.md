----------------------------------------------------------------------------------------------
## Discontinued

I decided to discontinue the development of this tool to concentrate my efforts on others one projects.

Please fell free to clone this repository and continue the development of this tool.

----------------------------------------------------------------------------------------------

<p align="center">
  <img src="https://raw.githubusercontent.com/tiagorlampert/sAINT/master/content/logo.png">
</p>

<h1 align="center">(s)AINT</h1>
<p align="center">
  <a href="https://www.java.com">
    <img src="https://img.shields.io/badge/Java-8-red.svg">
  </a>
  <a href="https://github.com/tiagorlampert/sAINT/blob/master/LICENSE">
    <img src="https://img.shields.io/badge/License-BSD%203-lightgrey.svg">
  </a>
  <a href="https://github.com/tiagorlampert/sAINT/tree/master/src_template/main/java/saint">
    <img src="https://img.shields.io/badge/Release-1.0-blue.svg">
  </a>
    <a href="https://opensource.org/licenses/BSD-3-Clause">
    <img src="https://img.shields.io/badge/Open%20Source-%E2%9D%A4-brightgreen.svg">
  </a>
</p>

<p align="center">
  (s)AINT is a Spyware Generator for Windows systems written in Java.
</p>

## Disclaimer
<p align="center">
  :computer: This project was created only for good purposes and personal use.
</p>

THIS SOFTWARE IS PROVIDED "AS IS" WITHOUT WARRANTY OF ANY KIND. YOU MAY USE THIS SOFTWARE AT YOUR OWN RISK. THE USE IS COMPLETE RESPONSIBILITY OF THE END-USER. THE DEVELOPERS ASSUME NO LIABILITY AND ARE NOT RESPONSIBLE FOR ANY MISUSE OR DAMAGE CAUSED BY THIS PROGRAM.

## Features
- [x] Keylogger
- [x] Take Screenshot
- [x] Webcam Capture
- [x] Persistence

## Tested On
[![Kali)](https://www.google.com/s2/favicons?domain=https://www.kali.org/)](https://www.kali.org) **Kali Linux - ROLLING EDITION**

## How To Use
```bash
# Install dependencies (you need Maven and JDK 8 package installed)
$ apt install maven default-jdk default-jre openjdk-8-jdk openjdk-8-jre -y

# To generate a .EXE using launch4j are necessary the following packages
$ apt install zlib1g-dev libncurses5-dev lib32z1 lib32ncurses6 -y

# Clone this repository
$ git clone https://github.com/tiagorlampert/sAINT.git

# Go into the repository
$ cd sAINT

# Install and configure Maven libraries
$ chmod +x configure.sh
$ ./configure.sh

# Run
$ java -jar sAINT.jar
```
## Note
* On Windows, install the latest <a href="https://www.java.com/en/download/">Java JRE 8</a> from Oracle.
* E-mail will be sent when it reaches the specified number of characters.
* Optionally you can enable Screenshot, Webcam Capture and Persistence.

## FAQ
> #### Why does the .EXE need java on target machine to run?
> The JRE is required and the executable will not work without it. Because the Windows need JRE for translating the program from java byte code to machine language.

## Screenshot
  <h3 align="center"> Maven dependencies</h3>
  
  <p align="center"> <img src="https://github.com/tiagorlampert/sAINT/blob/master/content/1.gif"> </p>
  
  <h3 align="center"> Generate spyware</h3>
  
  <p align="center"> <img src="https://github.com/tiagorlampert/sAINT/blob/master/content/2.gif"> </p>

## Run
<h3 align="center">Install Java JRE 8</h3>

<p align="center">
  <img src="https://github.com/tiagorlampert/sAINT/blob/master/content/jre.gif">
</p>

<h3 align="center">Run .EXE</h3>

<p align="center">
  <img src="https://github.com/tiagorlampert/sAINT/blob/master/content/3.gif">
</p>

<h3 align="center">or Run .JAR</h3>

<p align="center">
  <img src="https://github.com/tiagorlampert/sAINT/blob/master/content/4.gif">
</p>


## Data
<h3 align="center">Local</h3>

<p align="center">
  <img src="https://github.com/tiagorlampert/sAINT/blob/master/content/5.gif">
</p>


<h3 align="center"> E-mail</h3>

<p align="center">
  <img src="https://github.com/tiagorlampert/sAINT/blob/master/content/6.gif">
</p>

## How to uninstall
To uninstall run <a href="https://github.com/tiagorlampert/sAINT/blob/master/content/UNINSTALL.bat">UNINSTALL.bat</a> with administrative permissions.

## Contact
:email: **olegdargas@gmail.com**
