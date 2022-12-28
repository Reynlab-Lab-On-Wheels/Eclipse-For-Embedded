# Eclipse For Embedded

## Step 1 download java 
- Download from 

## Step 2 Create a folder named Oracle and copy java
- Open my computer.
- In the path put %APPDATA% and click enter.
- Create a folder named Oracle
- Inside the oracle folder extract the jdk-19.0.1 folder

## Step 3 Add java to syspath
- Open command prompt as admin.
- Run the following cmds
```
set Path=%APPDATA%\Oracle\jdk-19.0.1\bin;%Path%
setx Path "%APPDATA%\Oracle\jdk-19.0.1\bin;%Path%"
```
- verify by running the ```java --version``` cmd
### Step 4 Install Node 
- Download and install node js 
