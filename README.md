# Performance Testing with JMeter

Automated performance tests of an e-commerce application built using **Apache JMeter**.

## Table of Contents

- [Prerequisites](#prerequisites)
- [System Under Test (SUT)](#system-under-test-sut)
- [Download the project](#download-the-project)
- [Run tests](#run-tests)
  
## Prerequisites

Install the following prerequisites:

1. [Oracle JDK](https://www.oracle.com/java/technologies/downloads/) or [OpenJDK](https://openjdk.org/)
2. [Node.js](https://nodejs.org/en/)
3. [PostgreSQL](https://www.postgresql.org/download/)
4. [Visual Studio Code](https://code.visualstudio.com/download)
5. [Apache JMeter](https://jmeter.apache.org/download_jmeter.cgi)

## System Under Test (SUT)

The system under test (SUT) is this [e-commerce application](https://github.com/mgrybel/ecommerce-website) built using **Spring Boot 3** and **React 18**, which uses a **PostgreSQL** database to store data.

To run tests in this project, you must first install and run the SUT. Follow [these steps](https://github.com/mgrybel/ecommerce-website/blob/master/README.md).

## Download the project

Download the ZIP file and unzip the project.

Inside the ZIP file, you will find the **EcommerceWebsiteTestPlan.jmx** file, which is a JMeter test plan describing a series of steps JMeter will execute when run.

## Run tests

1. Open JMeter, and from the top menu, select **File** and then select **Open**.
2. In the Open window, select the **EcommerceWebsiteTestPlan.jmx** file that you have just downloaded, and click **Open**.
3. From the top menu, select **Run** and then select **Start**.

![plot](https://github.com/mgrybel/performance-testing-jmeter/blob/master/images/run.png?raw=true)
