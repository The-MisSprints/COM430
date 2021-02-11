# COM430-Metl Enhancement Project

## Table of Contents
* [Description](#description)
* [Diagrams](#diagrams)
* [Installation](#installation)
* [Usage](#usage)
* [Credits](#credits)
* [License](#license)

## <a name="description"></a>Description
The aim of this project is to enhance a whiteboard application currently in use, by providing the visualization necessary for early mathematics. In this enhanced version, educators are provided with a button to swtich between the blank whiteboard background and a graphed background, along with a few commonly used graphing tools. This will save educators valuable time setting up and provide clear environments for students to learn the new concepts at hand. 

## <a name="diagrams"></a>Diagrams
-Use Case Diagram\
![useCase](https://user-images.githubusercontent.com/77589392/107673970-788d7d00-6c64-11eb-89d7-48b2730694fe.png)\
-User Activity Diagram\
![userActivityDiagram](https://user-images.githubusercontent.com/77589392/107674077-93f88800-6c64-11eb-9154-c95d855541f3.png)\
-Activity Diagram\
![activityDiagram(1)](https://user-images.githubusercontent.com/77589392/107674132-a4106780-6c64-11eb-8b5b-b462210b04a3.png)\
-Communication Diagram\
![communicationDiagram](https://user-images.githubusercontent.com/77589392/107674178-b1c5ed00-6c64-11eb-8488-ce718b982822.png)\
-Context Diagram\
![ContextDiagram](https://user-images.githubusercontent.com/77589392/107674210-bab6be80-6c64-11eb-8582-6f91c0f3dd6c.png)\
-Architecture Diagram\
![Architecture](https://user-images.githubusercontent.com/77589392/107674439-f782b580-6c64-11eb-95fc-7159e57eec4a.png)\
![application](https://user-images.githubusercontent.com/77589392/107674813-5f390080-6c65-11eb-8c62-c011f758beb8.png)\
![infrastructure](https://user-images.githubusercontent.com/77589392/107674854-6d871c80-6c65-11eb-9dbb-a4e9ba71a46b.png)

## <a name="installation"></a>Installation
* Install the following required tools prior to installation:
  * [Java JDK version 8.x](https://www.oracle.com/java/technologies/javase/javase-jdk8-downloads.html)
  * [Node Package Manager](https://www.npmjs.com/get-npm)
  * [SBT](https://www.scala-sbt.org/)
* Clone the repository via command line:
```
  cd /Path/to/desired/location
  git clone https://github.com/The-MisSprints/COM430.git
```
* Some additional configuration will be needed:
```
  cd Path\to\your\repository
  set IVY_HOME=\ivyHome
  cd config
  copy configuration.sample.xml comfiguration.local.xml
  cd .. 
  sbt
```

## <a name="usage"></a>Usage
* To run a local (development) server for this app, use:
```
  sbt container:start
```
* Other useful commands include:
```
  sbt container:stop and sbt container:restart
```

## <a name="credits"></a>Credits
* Mark Pate
* Rebecca Walters

## <a name="license"></a>License
