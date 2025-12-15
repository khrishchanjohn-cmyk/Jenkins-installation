# Jenkins-installation
---

Jenkins requires Java to run, yet not all Linux distributions include Java by default. Additionally, not all Java versions are compatible with Jenkins.

There are multiple Java implementations that you can use. OpenJDK is the most popular one at the moment, we will use it in this guide.

Update the Debian apt repositories, install OpenJDK 21, and check the installation using the following commands:

```sh
sudo apt update
sudo apt install fontconfig openjdk-21-jre
java -version
```

