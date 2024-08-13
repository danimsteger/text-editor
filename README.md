# Text Editor

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## Description

This project involved modifying starter code to make an application progressive and installable by adding a functioning service worker and manifest. This project utilized IndexedDB as the database, used Express.js, Node, Webpack, and several of its supporting modules.

The application was deployed to render and can be viewed [here](https://text-editor-x702.onrender.com).

![sample of text editor](/images/webapp.png)

---

---

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Credits](#credits)
- [License](#license)

---

---

## Installation

### Clone this repository

```
git clone git@github.com:danimsteger/text-editor.git
```

### Go into this repository

```
cd text-editor
```

### Access code of the repository

```
code .
```

### Install Necessary Dependencies on local device

```
npm install
```

---

---

## Usage

To view a the deployed application via render, click [here](https://text-editor-x702.onrender.com).

To view the program, navigate to the cloned repository.

### Start Application:

```
npm run  start
```

Once the application has been started, users can navigate to the text editor via the link [here](https://text-editor-x702.onrender.com).

Users can install the application to their own devices via the 'install' button or by clicking this button ![sample of install](/images/button.png).

This will download and open the application on its own, outside of the browser and the application will look like this:
![sample of downloaded applicaton](/images/installedapp.png)

Users can add text to the editor and it will be saved to the indexedDB database.

![sample image of indexedDB](/images/indexedDB.png)

The application is downloaded because of the working service worker and manifest. The service worker and manifest can be viewed using Chrome Dev Tools.

![sample view of service work](/images/serviceworker.png)
![sample view of manifest](/images/manifest.png)

## Credits

This project was created by Danielle Steger. To complete this project, several resources were referenced, adopted, and modified. Specifically, materials provided in Module 19 of edX Boot Camps LLC, specifically Activity 28, were referenced and modified. Additionally, several articles on "MDN Web Docs" and "W3Schools" were referenced. Specific articles are listed below. This project was completed with the use of Webpack Configurations and the corresponding documentation was referenced as well.

Additionally, our professor gave us some assistance with the creation of the service worker, src-sw.js file.

## License

Distributed under the MIT License. See [LICENSE](LICENSE).
