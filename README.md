# hybrid-app-checklist
Checklist should have to configured ionic framework &amp; angularJS in action to build mobile app for Android and IOS

## List to download
**1) SDK manager tools** - **Cumpolsary** (download and install)
  - Used to add platform and build code into .apk files
  - Link to download : http://dl.google.com/android/installer_r24.4.1-windows.exe
  - Should install in bigger storage space to hold the Api revision at least minimun have 10 to 20GB free allocation space.

**2) JDK(already included JRE)** - **Cumpolsary** : choose either x64 or x86 depend on your Operating System.(Download and install)
  - x86(32bit) http://download.oracle.com/otn-pub/java/jdk/8u65-b17/jdk-8u65-windows-i586.exe
  - x64(64bit) http://download.oracle.com/otn-pub/java/jdk/8u65-b17/jdk-8u65-windows-x64.exe

**3) Ant apache(Download only)**  - **Cumpolsary** 
  - http://www.us.apache.org/dist//ant/binaries/apache-ant-1.9.6-bin.zip
   
**4) Node.js(download and install)**  - **Cumpolsary** 
  - Used to install Ionic & Cordova by using NPM
  - https://nodejs.org/dist/v4.2.4/node-v4.2.4-x86.msi

**5) download sublime text 3, choose either x64 or x86 depend on your Operating System**.(download and install)**(optional)**
   - Just Editor
   - x86(32bit) http://c758482.r82.cf2.rackcdn.com/Sublime%20Text%20Build%203083%20Setup.exe
   - x64(64bit) http://c758482.r82.cf2.rackcdn.com/Sublime%20Text%20Build%203083%20x64%20Setup.exe

**6) Xampp or Any server(to host API)**

## Install Ionic & Cordova
**1) Install cordova**
   - Open command prompt(CMD), command : `win + r`, type `cmd` and `enter`.
   - Type : `npm install -g cordova, and wait until finish.`

**2) Install ionic**
   - Open command prompt(CMD), command : `win + r`, type `cmd` and `enter`.
   - Type : `npm install -g ionic, and wait until finish.`

## Setting Up Path ANDROID_HOME, ANT_HOME and JDK
**- General Uses**
  - Right Click `My Computer ==> Properties ==> Advanced System Settings ==> Environment Variables`
  
**1) ANDROID_HOME**
  - In User variables
    - Click `New ==> variable name put "ANDROID_HOME" without quote ==> variable value put "E:\**\Android\android-sdk" without quote(location of SDK path installed)`
  - In System Variables
    - Find variable name path, add variable value at the end with this portion text `"%ANDROID_HOME%tools;%ANDROID_HOME%platform-tools;"` without quote and separate with semicolumn(;)
  
**2) ANT_HOME**
  - In User variables
    - Click `New ==> variable name put "ANT_HOME" without quote ==> variable value put "E:\**\apache-ant-1.9.6" without quote(location of ANT was located after unzipped)`
  - In System Variables
    - Find variable name path, add variable value at the end with this portion text `"%ANT_HOME%;"` without quote and separate with semicolumn(;)
  
**3) JAVA_HOME ( Ussually already configured automatically after installation process), if did't use below configuration :**
  - In User variables
    - Click `New ==> variable name put "JAVA_HOME" without quote ==> variable value put "C:\Program Files (x86)\Java\jdk1.8.0_65" without quote(location of JDK path installed before)`
  - In System Variables
    - Find variable name path, add variable value at the end with this portion text `"%JAVA_HOME%\bin;"` without quote and separate with semicolumn(;)
  
More steps? Nope, that's all.... Happy Coding :)
