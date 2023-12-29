# Burp Suite Professional 1.4.34

<!-- contact me -->
<details open>
 <summary><img src="https://media.giphy.com/media/iY8CRBdQXODJSCERIr/giphy.gif" width="30px">&nbsp;Contact me ....</summary>
<div>
  <samp>
    <h2 align="center">you can reach me by:</h2>
    <p align="center">
      <br/>
      <a href="https://www.linkedin.com/in/aminul-islam-270816239/" target="blank"><img align="center"
         src="https://img.shields.io/badge/linkedin-%231DA1F2.svg?style=for-the-badge&logo=linkedin&logoColor=white"
         alt="azzar" height="30"/></a>
      <a href="https://www.facebook.com/aimehedi75" target="blank"><img align="center"
         src="https://img.shields.io/badge/facebook-4267B2.svg?style=for-the-badge&logo=facebook&logoColor=white"
         alt="azzar" height="30"/></a>
      <a href="aminulislam0527@gmail.com" target="blank"><img align="center"
         src="https://img.shields.io/badge/gmail-EA4335.svg?style=for-the-badge&logo=gmail&logoColor=white"
         alt="azzar" height="30"/></a>
    </p>
  <p align="center">
      <a href="https://www.instagram.com/ai_mehedi_hasan/" target="blank"><img align="center"
         src="https://img.shields.io/badge/instagram-%23E4405F.svg?style=for-the-badge&logo=Instagram&logoColor=white"
         alt="azzar" height="30"/></a>
     
     
  </samp>
</div>
</details>

## Burp Suite Professional Short Description

Burp Suite Professional is a powerful cybersecurity tool designed for web application security testing. It provides a range of functionalities, including scanning for security vulnerabilities, intercepting and modifying HTTP traffic, and various tools for manual testing of web applications.

## Installation Steps for Linux

### Java 8 Download and Install

1. **Download Java JDK 8:**
   - Visit [OpenLogic's OpenJDK Downloads](https://www.openlogic.com/openjdk-downloads) to download Java JDK 8.

2. **Install Java JDK 8:**
   ```bash
   sudo dpkg -i downloaded_file.deb
   ```

3. **Select Java 8 as the Default Version:**
   ```bash
   sudo update-alternatives --config java
   ```
   - Select the option corresponding to Java 8 from the list.
   - ![Burp Suite Run](img/Screenshot_4.png)

4. **Verify Java Version:**
   ```bash
   java -version
   ```

   Ensure that the installed Java version is Java 8.

### Burp Suite Professional Installation

1. **Run Burp Suite Professional:**
   ```bash
   java -noverify -jar ESEdition.jar
   ```

   Click on the "Run" button when prompted.

   ![Burp Suite Run](img/Screenshot_5.png)
   ![Burp Suite Run](img/Screenshot_6.png)
   ![Burp Suite Run](img/Screenshot_7.png)
   ![Burp Suite Run](img/Screenshot_8.png)
   ![Burp Suite Run](img/Screenshot_9.png)
   ![Burp Suite Run](img/Screenshot_10.png)
   ![Burp Suite Run](img/Screenshot_11.png)

3. **Make the Script Executable:**
   ```bash
   sudo chmod +x burp.sh
   ```

4. **Open Burp Suite Professional:**
   ```bash
   ./burp.sh
   ```

   Burp Suite Professional is now ready to use.
