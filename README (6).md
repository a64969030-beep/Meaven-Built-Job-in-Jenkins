# Jenkins Maven HelloWorld

## Project Structure
- src/main/java/HelloWorld.java
- pom.xml
- screenshots/build_success.png

## How to Build in Jenkins
1. Install Jenkins and Maven (Global Tool Configuration).
2. Create a Freestyle project.
3. In **Source Code Management**, select "None" (or use local workspace).
4. In **Build**, choose **Invoke top-level Maven targets**.
5. Goals: `clean package`
6. Save and click **Build Now**.
7. Check Console Output → should show **BUILD SUCCESS**.

## Expected Output
```
Hello, Jenkins + Maven!
BUILD SUCCESS
```
