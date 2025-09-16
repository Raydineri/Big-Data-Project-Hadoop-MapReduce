# 🚀 Big Data Project: Hadoop MapReduce with Spring Boot

[![Hadoop](https://img.shields.io/badge/Hadoop-3.3.6-yellow.svg)](https://hadoop.apache.org/)
[![Spring Boot](https://img.shields.io/badge/Spring%20Boot-2.7.0-brightgreen.svg)](https://spring.io/projects/spring-boot)
[![Java](https://img.shields.io/badge/Java-17-blue.svg)](https://www.oracle.com/java/)
[![Maven](https://img.shields.io/badge/Maven-Build-brightgreen.svg)](https://maven.apache.org/)

## 📖 About

This project demonstrates how to:
- 🖥️ Install and configure **Hadoop** on a cluster (1 master, 2 slaves) 
- ⚡ Run a **Spring Boot** application that executes a MapReduce job
- 📊 Process a real-world dataset from **Kaggle**

## 🛠️ Technologies Used

- Hadoop
- Java
- Maven
- Spring Boot

## 🏗️ Project Structure

```
hadoop_mapreduce/
├── pom.xml
├── README.md
├── src/
│   ├── main/
│   │   ├── java/
│   │   │   ├── IntSumReducer.java
│   │   │   ├── TokenizerMapper.java
│   │   │   ├── WordCount.java
│   │   │   └── org/example/App.java
│   │   └── resources/
│   │       └── input/
│   │           ├── file.txt
│   │           └── output/
│   │               ├── _SUCCESS
│   │               └── part-r-00000
│   └── test/
│       └── java/org/example/AppTest.java
└── target/
```

## 📦 How to Run

1. **Install Hadoop** and set up your cluster (1 master, 2 slaves).
2. **Clone this repository** and import it into your IDE.
3. **Build the project**:
   ```sh
   mvn clean package
   ```
4. **Run the Spring Boot application** to execute the MapReduce job:
   ```sh
   java -jar target/wordcount-1.0-SNAPSHOT.jar
   ```
5. **Check the output** in `src/main/resources/input/output/part-r-00000`.

## 📹 Demo Video

Watch the full tutorial here: [Project Video](https://drive.google.com/file/d/1z1UHO1iTZa1-KebYIhhBxEhiWdBETn-6/view?usp=sharing) 🎬

> In the demo video, you will find an explanation on how to install Hadoop, set up a cluster with one master and two slaves, and run a MapReduce job.

## 📂 Dataset

- The dataset used is from [Kaggle](https://www.kaggle.com/).

## ✨ Features

- Distributed processing with Hadoop
- Integration with Spring Boot
- Real-world data analysis

## 🤝 Contributing

Pull requests are welcome!

---

Made by Rayen Ben othman with ❤️ for Big Data enthusiasts!
