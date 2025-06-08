# Task 8 – Java Maven Build in Jenkins

## 📄 Objective
Build a simple Java Hello World app using Maven in Jenkins on an EC2 instance.

## 📁 Project Structure
```
hello-java-maven/
├── pom.xml
├── src/main/java/HelloWorld.java
```

## 🔧 Jenkins Setup
- Jenkins installed via Docker on EC2
- Maven installed inside the Jenkins container
- Freestyle project created with:
  - Build step: **Execute Shell**
  - Command:
    ```bash
    cd /var/jenkins_home/workspace/HelloJava
    mvn clean package
    ```

## ✅ Output
The job successfully ran with:
```
[INFO] BUILD SUCCESS
```

## 📸 Screenshot
(Upload screenshot.png in this repo after successful build)
