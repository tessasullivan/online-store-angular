# Online Music Store
###by Tessa Sullivan

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 1.6.5.  An Epicodus in class project.

Users can view, add, edit, and delete albums.

##Specifications
| User stories | Action | Expected Result
| :-------------| :------------- | :-------------|
| User can see Welcome screen | Open localhost:4200 | Welcome screen displayed with menu options 'About', 'Marketplace', 'Admin'|
| User can view About (us) | Select About from the nav bar | The about page is displayed |
| User can view albums | Select Marketplace from nav bar | List of albums in database is listed |
| User can view album details | From Marketplace, select an album | Album details are displayed |
| User can add albums | Select Admin from lower nav bar, fill in form | Album is added to the inventory and is listed below |
| User can edit albums | Select Admin from lower nav bar, make changes to a field and click Update | Album information is changed |
| User can delete albums | Select Admin from lower nav bar and click delete on an album | User is asked to confirm and, if 'ok' is entered, the album is deleted |

## Setup/Installation Requirements
### Prerequisites
You must have Node.js installed.  Go to [Node.js](https://nodejs.org/en/download/current/) and download and install the appropriate version for your OS.

### Installation
1. Clone this repository.
2. ```cd online-store-angular```
3. Run ```npm install```.


### Firebase
You must have a Firebase account and create a database in order to use this application.

1. Login to http://firebase.google.com.
2. ```Add a project``` (if prompted, web app as the type of project).
3. On left hand menu, click ```Database```
4. Create a Realtime Database by clicking ```Create database``` in that section.
5. Select ```Start in test mode``` and click ```Enable```.
6. Upload sample data to your Firebase.  On the ```Data``` tab, select the icon which is 3 vertical dots and choose ```Import JSON```.
7. Browse to ```online-store-angular/src/app``` and select ```sample-albums.json```.
8. ```Import``` the file.

### Running the app
Run ```ng serve -o```.  This will open the application in a new browser window.

## Known Issues
No known issues at this time.  This is a barebones application meant to practice Angular and Firebase.

## Technologies Used

* AngularJS
* Firebase
* Javascript
* HTML / CSS

## Support and contact details

_Contact Tessa Sullivan @ tessa.sullivan@gmail.com_


### License

*{This software is licensed under the MIT license}*

Copyright (c) 2019 **_Tessa Sullivan_**
