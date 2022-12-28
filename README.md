# Installing Eclipse For Embedded

## Step 1 download java 
- Download from https://github.com/Reynlab-Lab-On-Wheels/Eclipse-For-Embedded/raw/main/node-v18.12.1-x64.msi

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
- Download and install node js https://github.com/Reynlab-Lab-On-Wheels/Eclipse-For-Embedded/raw/main/node-v18.12.1-x64.msi
- Run run the follwing cmds ```npm install --global xpm@latest```
- Install these toolchains one by one using the cmds.
```
xpm install --global @xpack-dev-tools/windows-build-tools@latest

xpm install --global @xpack-dev-tools/arm-none-eabi-gcc@latest --verbose
xpm install --global @xpack-dev-tools/qemu-arm@latest --verbose
xpm install --global @xpack-dev-tools/openocd@latest --verbose
xpm install --global @xpack-dev-tools/riscv-none-embed-gcc@latest --verbose
xpm install --global @xpack-dev-tools/cmake@latest --verbose
xpm install --global @xpack-dev-tools/ninja-build@latest --verbose
xpm install --global @xpack-dev-tools/meson-build@latest --verbose
```

## Step 5 Install Eclipse
- Download Eclipse From https://ftp.yz.yamagata-u.ac.jp/pub/eclipse/technology/epp/downloads/release/2022-12/R/eclipse-embedcpp-2022-12-R-win32-x86_64.zip
- Extract to the desired destination and run Eclipse.exe

## Demo Video
https://github.com/Reynlab-Lab-On-Wheels/Eclipse-For-Embedded/blob/main/Eclipse_Install_Windows.mp4?raw=true
