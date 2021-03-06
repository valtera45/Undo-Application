# Undo Application

An application that demonstrates 'undo' functionality.  There are three buttons and when pressed each
generates a random color.  When each button is pressed, the previous color for the button is preserved 
in a stack (LIFO); each button's previous state is restored when the undo button is pressed.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Prerequisites

* Java 8 or higher
* Maven

### Installing

Pull down the repository to a local directory

```
git clone https://github.com/valtera45/Undo-Application.git
cd Undo-Application
mvn clean install
```

Next run the application...

```
java -jar target/UndoApp-jar-with-dependencies.jar
```

## Built With

* [Maven](https://maven.apache.org/) - Dependency Management

## Authors

* **Chris Wright** -- [valtera45](https://github.com/valtera45)
