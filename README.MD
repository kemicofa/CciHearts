#  Cci Hearts

Cci Hearts is a start up company where you've just been hired ! Congratulations. They're focused on working with web technologies and conencted objects.

## Company Goal

Cci Hearts goal is to connect everyone's hearts. What's the point of this project ? Who knows and who cares. You're getting paid to develop this awesome project.

## Technologies

*Please note that this list of technologies are simply recommendations*

### Web Services
* nodejs
* docker/docker-compose
* [redis](https://redis.io/)
* [socket.io](https://socket.io/)

### Cross Platform Mobile Development
 * [react-native](https://facebook.github.io/react-native/)
 * [realmjs](https://github.com/realm/realm-js)
 * [yarn](https://yarnpkg.com/lang/en/)
 * [nodejs](https://nodejs.org/en/) (6,8 or 10)
 * npm (installed with nodejs)

 ### React Native Libraries
 * [react-native-ble-manager](https://github.com/innoveit/react-native-ble-manager)
 * [mobx/mobx-react](https://github.com/mobxjs/mobx-react)
 * [react-navigation](https://reactnavigation.org/)


## Tasks

### Your first task

Cci Hearts has invested some money in the new Amazfit Bit watch and would like you to build a PoC (Proof of Concept) application that can continously receive heartbeat information.

1. Ensure you have the required user permissions on Anroid/iOS accessing Bluetooth modules

### Your second task

The CEO has doubled down on this project and decides to invest more into it. You're tasked in creating a convincing and smoothe UI (User Interface).

#### When working on the different components:

* Focus on making REUSABLE components

#### Create the following components:

* Bluetooth Component
    a. Automatically Enable Bluetooth on Android / Request bluetooth on iOS
    b. Shows list of available Bluetooth devices if no device is currently connected
    c. Shows list of device information if a device is currently connected
    c. Show current bluetooth status
    d. Select and connect to device
    f. Discover Services and Characteristics
    e. Automatically disconnect if the device is NOT an Amazfit Bip Watch

* Layout Components
    a. Container
    b. Header
    c. Content
    d. Footer

#### Create the following views:

1. Authentication View
    a. Email Input
    b. Password Input
    c. Background Cover Image
    d. Implement [Keyboard Avoiding View](https://facebook.github.io/react-native/docs/keyboardavoidingview.html)

2. Switch Navigator View
    a. Depending on authentication, redirect to login or to the home page.

3. Home View
    a. Shows map with nearby users and their heartbeat information
    b. Shows icon with connection information about watch
        1. Icon also happens to be a button that redirects user to the Bluetooth view

4. Bluetooth View
    a. Uses Bluetooth Component
5. Settings View
    a.
