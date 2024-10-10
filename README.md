# Installation guide for wca4ej 

This document gives infomration on installing software tools/IDE that are needed to run ***Watson Code Assistant For Enterprise Java*** **(Wca4ej)**
## Environment setup 

### 1. Java installation

Install Java21 using this link [Download Java](https://www.oracle.com/sg/java/technologies/downloads/)
> Note: After installing java,add java to `PATH` variable and set `JAVA_HOME` envitonment variable
### 2. Install Maven

- Windows
    - Visit the official Maven website: [Maven Download Page](https://maven.apache.org/download.cgi)
    - Under "Files", click on the binary zip archive link (e.g., apache-maven-x.x.x-bin.zip). 
    - Extract the zip file to a location of your choice, e.g., C:\Program Files\Apache\maven.
    - Add Maven to PATH and Set MAVEN_HOME variable 
- Mac
   - Install maven using homebrew

### 3. Install Eclipse

Eclipse users must install one of these two packages:
   - Eclipse IDE for Java Developers
   - Eclipse IDE for Enterprise Java and Web Developers 

Below are the links for eclipse installation
- [Eclipse 2024-03](https://www.eclipse.org/downloads/packages/release/2024-03/r)
- [Eclipse 2023-12](https://www.eclipse.org/downloads/packages/release/2023-12/r)

### 4. Download Wca4ej extension

Download the latest WCA4EJ Code Eclipse Extension and install by following these instructions: [Wca4ej Extension](https://early-access.ibm.com/software/support/trial/cst/welcomepage.wss?siteId=2044)

> Note: If you see a yellow warning: checking file that doesn’t go away; hit refresh & try again

### 5. Installing Wca4ej extension

After downloding the extension from **Step 4** and getting API key from **Step 5** install the wca4ej using eclipse as shown below ![screenshot](./images/1.InstallNewSw.png)

Choose the loacl package or archive and provide the path where the extension files are downloaded from **Step 4** 
![screenshot](./images/2.LocateLocalPackage.png)

After the software (extension gets installed), restart your IDE. After restart, navigate to below setting 

![screenshot](./images/4.ChooseviewEclipse.png)

Then choose the Watson code assistant for enterprise java as below

![screenshot](./images/5.ShowWca4ejChatView.png)

After this, you will be navigated to below screen, input the API key created in **Step 5**
![screenshot](./images/3.Wca4ejchat.png)

### 7. Installing Liberty Tools

Install the liberty tools from eclipse market place as shown below [Help >> Eclipse Marketplace]
![screenshot](./images/6.LibertyTools.png)


Now, you can start using wca4ej

You can import the existing maven project, after that based on the your requirement, choose the feature you need.
![screenshot](./images/7.Wca4ejFunctionalites.png)



