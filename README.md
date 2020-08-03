# Welcome to Online/Offline Budget Tracker!

[![Generic badge](https://img.shields.io/badge/Version-1.0.0-GREEN.svg)](https://shields.io/)
[![MIT license](https://img.shields.io/badge/License-MIT-blue.svg)](https://lbesson.mit-license.org/)
1. [ Description ](#desc)
2. [ Installation ](#install)
3. [ Usage ](#usage)
4. [ License ](#license)
5. [ Contributing ](#contribute)
6. [ Tests ](#test)
7. [ Questions ](#question)

<a name="desc"></a>
# 1. Description 

This is a progress web app storing the user's transaction histories and displaying net amount of the user's assets. 

By using manifest and service worker, this app is able to cache the user's input locally at indexeddb while the device is offline. And once it's back to online, push local data to backend mongoDB database. 

![capture](capture.gif)

<a name="install"></a>
# 2. Installation 

```
npm install
```

<a name="usage"></a>
# 3. Usage 

The app is hosted at Heroku: [Budget Tracker](https://nobobobo-budget-tracker.herokuapp.com/)


<a name="license"></a>
# 4. License 

© 2020 Noboru Hayashi All Rights Reserved.

This project is MIT License licensed. 

<a name="contribute"></a>
# 5. Contributing 

Contributions, issues and feature requests are welcome!

Feel free to check [issues page](https://github.com/nobobobo/online-offline-budget-tracker/issues).<a name="test"></a>
# 6. Tests 

```
npm run test
```

<a name="question"></a>
# 7. Questions

![Image of nobobobo](https://github.com/nobobobo.png?size=50)

If you have any question about this project, please feel free to contact **Noboru Hayashi** via [Email](mailto:ianhsu1221@gmail.com).

---

_This README was generated with [readme-generator](https://github.com/nobobobo/readme-generator)_