# 19 Progressive Web Applications (PWA): Text Editor
![Github license](https://img.shields.io/badge/License-MIT-yellow.svg)

## Description
To further my knowledge of Progressive Web Apps, I built a text editor that runs in the browser, and that meets the core technical criteria to be a PWA, which are as follows: <br>
1. Has a web manifest file <br>
2. Be served using https <br>
3. Register a service worker with a fetch event handler <br>

Additionally, my application will also function offline.

For this application, I used IndexedDB to store data. I also installed idb to help with retrieving and storing data in IndexedDB. 

## User Story

```md
AS A developer
I WANT to create notes or code snippets with or without an internet connection
SO THAT I can reliably retrieve them for later use
```

## Installation
You can find the dependencies I've installed for this project in the package.json's.

## Usage

[Here is the deployed application.](https://week-19-challenge.herokuapp.com/)

Once you're on the web page, you can enter any text in the text editor, and that data will be saved if you click anywhere outside the DOM window. To dowload the application, to be used outside of the browser, you can click the Install button or click the install icon on the right hand side of the url bar.

Here is what the application looks like on the browser.
![image of app on the browser](assets/browser-image.png)

Here is what the application looks like after installed.
![image of app outside of browser](assets/installed-app-image.png)

## Credits

N/A

## License

This application is covered under the MIT license.