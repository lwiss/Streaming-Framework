# README #

The audio streaming framework consists of an Android application and a Java app Server. The main goal of the framework is to build a distributed system that control several android phones as well as run algorithms for beam-forming, speech enhancement, etc... 
In order to achieve our goal, a streaming framework that is able to stream high quality audio data and launch real time computations on the server has been developed.   
The framework offers these main features:

* **Easy way to control the connected smartphones and sending detailed instructions such as: **

     * **Record high quality audio data and stream it in real time to the server**

     * **Stream high quality audio data to the Android phones from the server**

     * **Redirect audio streams between phones**

* **Display real time Fourier transform of the streamed signals**

The architecture of the framework has been made such that everything is controlled by the server. The server sends detailed instructions to the phones to perform certain operations such as recording and streaming audio with specific parameters. 
The configuration of the framework has been made as simple as possible. The user has just to start the server application and then run the Android app in the phone, all connections will be made automatically.

The framework can be used by beginners, students or researchers to either play with audio signals and observe some interesting properties in such as the real time display of the Fourier transform or to run advanced experiments such as the computation of the room impulse response.   
The framework is still under development and not all signal processing algorithms are integrated.

### How do I get set up? ###

* Summary of set up
* Configuration
* Dependencies
* Database configuration
* How to run tests
* Deployment instructions

### Contribution guidelines ###

* Writing tests
* Code review
* Other guidelines

### Who do I talk to? ###

* Repo owner or admin
* Other community or team contact