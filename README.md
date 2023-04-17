# JPA-Hibernate Example Project

This is a sample project demonstrating how to use JPA and Hibernate to implement persistence in a Java application. The project includes 2 sample entities and can be used as a starting point for learning JPA and Hibernate.

* This JPA and Hibernate example project was created as a part of a training course on these technologies, which I'm teaching as the instructor.
* This project can be easily cloned and imported into IntelliJ IDEA Community Edition, allowing users to explore and experiment with JPA and Hibernate in a Java project without any additional setup.


Please check out the [java-course](https://github.com/ikramdagci/java-course) repository for more Java programming resources and examples!


## Getting Started

## Creating a JPA Project in IntelliJ IDEA Community Edition

To import the project into IntelliJ IDEA Community Edition:

1. Clone the repository using `git clone https://github.com/ikramdagci/jpa-hibernate-introduction`
2. Open IntelliJ IDEA Community Edition and select "Open or Import"
3. Navigate to the directory where you cloned the project and select the "pom.xml" file to import the project as a Maven project
4. Before running the project, make sure to update the relevant configuration information in the `./src/main/resources/META-INF/persistence.xml` file for JPA and `./src/main/resources/hibernate.cfg.xml` file for Hibernate. This includes the database username, password, URL, dialect, and driver_class.
5. Additionally, since this sample project uses PostgreSQL, the `postgresql` JDBC driver dependency in the `pom.xml` file should be updated according to the database vendor being used by the user.
6. Once you have updated the configurations, you should be able to run the project and experiment with JPA and Hibernate.

### Prerequisites

To run this project, you will need to have the following software installed:

* Java 8 or higher
* Maven

### Installing

To install this project, clone the repository and navigate to the project directory. Then, run the following command:

```mvn clean install```


This will download any necessary dependencies and compile the project.

### Running the Project

After the compilation process is completed, you can run the project by executing the `main()` method in the `Driver` class.

## Built With

* Java 8
* Maven
* JPA
* Hibernate

## Acknowledgments

* This project was created for educational purposes, as a part of a JPA and Hibernate training course.
* Special thanks to the creators and contributors of JPA and Hibernate, as well as the wider Java and open-source communities.

