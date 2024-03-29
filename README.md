# Notes App Demo

This Notes app demo is a basic demonstration using on JS and HTML.

##  Prerequisites

You will need the following software insalled on your computer:

- git: [https://git-scm.com/](https://git-scm.com/)
- Node.js and NPM [https://nodejs.org/en/](https://nodejs.org/en/)

Recommended:

- VS Code.  This really is one of the best code editors out there for web (and other) programming.   Lightweight, fast and with an extensive library of language support, autocomplete and linter plugins.

    [https://code.visualstudio.com/](https://code.visualstudio.com/)

---

##  Installation

You can grab the code for this app from https://github.com/StuLast/Notes-App-Demo

```git clone https://github.com/StuLast/Notes-App-Demo```

Once downloaded, run the following to make sure all the packages are installed.

```npm i```

---

##  Running locally

The repo has been configured to use webpack which contains a pseudo web-server, so can serve up the web application as if it were coming from a real web server.  This server also tracks changes and will reload automatically when changes are made.

The script to run the server has already been defined in the package.json file.  To run the server enter the following into a terminal/bash/console app.

```npm run dev-server```

This will start a local web server with the ip address http:/127.0.0.1:8080 and should automatically start up your default web browser.

---

##  Produciton Builds

To build for production, use `npm run build`.  This will package up all the files required for the application in the public_html folder.  The contents of the public_html folder are what should be copied over to any web hosting service.