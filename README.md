# ⚡ Electric VLSI Design Free Tool – Cross-Platform Installation Guide

This repository provides step-by-step instructions to **install and run Electric VLSI** on:

- 🐧 Linux (Ubuntu/Debian)
- 🪟 Windows 10/11
- 🍎 macOS (Intel/Apple Silicon)

> 🔧 Electric VLSI is a powerful open-source EDA tool for VLSI layout and schematic design, written in Java.

---

## 🔗 Downloads

- Official JAR (v9.07): [Electric VLSI Downloads Page](https://www.staticfreesoft.com/productsFree.html)
- Or clone this repo to use the `.jar` directly.

---

## ⚙️ Prerequisites

- ✅ **Java JDK** (8 or later)
- ✅ Internet connection for initial download

---

## ⚙️ Steps to Install and Run Electric VLSI Design Free tool on Linux ( e.g. Ubuntu )

### Step 1: Update your system

Always good practice to make sure your repositories are fresh.

```
sudo apt update && sudo apt upgrade -y
```

(for Ubuntu/Debian based systems; for Fedora/RHEL/CentOS, use sudo dnf update.)

### Step 2: Install Java

You have a couple of options:

- Default JDK (good enough for 99% cases like running .jar files)
- Specific JDK version (say OpenJDK 17 or 21 if your application needs a particular version)

#### Option 1: Install Default Java (Quickest way)

```
sudo apt install default-jdk -y
```
This installs the default Java Development Kit (JDK), which includes the Java Runtime Environment (JRE) needed to run .jar files.

You can check after installing:
```
java -version
```
You should see something like:
```
openjdk version "XX" 
```
#### Option 2: Install Specific Java Version (example: OpenJDK 17)

If you need a particular version:
```
sudo apt install openjdk-17-jdk -y
```
Similarly check:
```
java -version
```
Professional Tip:
JDK includes JRE, so you don't have to install JRE separately unless you only want the runtime.

### Step 3: Verify Java Installation
After installation, make sure Java is properly installed:
```
java -version
javac -version
```
java -version → shows Java Runtime

javac -version → shows Java Compiler (useful if you later want to compile .java files too).

### Step 4: Download Electric ( .jar file )

Download (.jar) file directly from this Repo or
Open this link and download the file ( .jar ): 

```
https://ftp.gnu.org/pub/gnu/electric/electric-9.08.jar
```

### Step 5: Run your .jar file
Assuming you have a .jar ready, just navigate to the directory containing your jar file and run:

```
java -jar electric-9.08.jar
```
Example:

```
cd Downloads
java -jar electric-9.08.jar
```
And boom! 🎯 it should run.

## ⚙️ Steps to Install and Run Electric VLSI Design Free tool on Windows 10/11:

- Download and install Java JDK

- Download electric.jar from: 
    - This repo or
    - official site: https://www.staticfreesoft.com/productsFree.html

- Double-click electric.jar to run.
- If it doesn't run:

    - Open Command Prompt:
    ```
    java -jar electric.jar
    ```
## 🍎 macOS Setup
```
brew install openjdk
brew link --force --overwrite openjdk

java -version   # confirm installation

# Download and run
curl -O https://www.staticfreesoft.com/jars/electricBinary.jar
java -jar electricBinary.jar
```
If GUI doesn’t open, allow permissions:

```
xattr -d com.apple.quarantine electricBinary.jar
```

## 💡 Tips

- 🔁 Always use the latest Java version compatible with Electric
- ⚠️ Avoid spaces in file paths (especially on Windows)
- 📂 Save all your layouts in a dedicated design folder
- 📝 Electric supports exporting to SPICE and GDS

## ⚡ Resources

- [Electric VLSI - Static Free Software Official Website](https://www.staticfreesoft.com/index.html)
- [Download Page](https://www.staticfreesoft.com/productsFree.html)
- [Electric VLSI Online User Manual](https://www.staticfreesoft.com/jmanual/)


## 🧠 Author
- Maintained by: Dutt Panchal
- 🔗 Email: dattpanchal2904@gmail.com
- 🔗 [LinkedIn](https://www.linkedin.com/in/dattpanchal04/) 
- 💻 [GitHub](https://github.com/DuttPanchal04)

## 📜 License
This repo is for educational purposes. Electric VLSI is © Static Free Software.
