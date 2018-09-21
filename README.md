# NEO Smart Contract Development Environment for Java Developers

In this tutorial, I will walk through how to set up a development environment to build NEO Smart Contracts using Java from the ground up. This tutorial is intended for developers ranging from beginners to experienced developers.

I will start with an introduction of the major components needed and then talk through setting up each step.  There are a few basic prerequisites.

### Prerequisites
* Java
* Maven (https://maven.apache.org/install.html)
* git (Strongly suggested)
* IDE (I will be using Eclipse)

This tutorial is targeted towards development on Mac/Linux; however, I will link to examples for Windows users.

**Note: At the end of each page, you will find a hyperlink to the next page.**

---

### Index
* [Introduction](1.Introduction.md)
* [NeoJ Compiler Setup](2.neoj-compiler.md)
* [NEO Devpack Java Setup](3.neo-devpack-java.md)
* [Build Template ICO](4.template-ico.md)
* [Simple NEO Docker Setup](5.1.simple-neo-docker.md)
* [Advanced NEO Docker Setup](5.2.advanced-neo-docker.md)
* [NEO Python CLI](6.neo-python-cli.md)
* [Smart Contract Execution](7.smart-contract-execution.md)

---

### Content Synopsis
* Download .Net Core
  - https://www.microsoft.com/net/download
* Download Visual Studio
  - https://visualstudio.microsoft.com
* Clone ```neo-compiler```
  - ```git clone https://github.com/neo-project/neo-compiler.git```
* Clone ```neo-devpack-java```
  - ```git clone https://github.com/neo-project/neo-devpack-java.git ```
* Clone Java Examples
  - ```git clone https://github.com/neo-project/examples-java.git```
* Download Docker for Mac
  - https://store.docker.com/editions/community/docker-ce-desktop-mac
* Build Docker image
  - ```docker pull cityofzion/neo-privatenet```
* Clone NEO Python and start ```neo-puthon```
  - ```git clone https://github.com/CityOfZion/neo-python.git```
* Deploy Smart Contract
  - ```import contract ico-template-1.0.0.avm 0710 05 True False```

---

**Next Section:** [Introduction](1.Introduction.md)
