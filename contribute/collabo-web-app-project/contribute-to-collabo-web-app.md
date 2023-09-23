---
description: CONTRIBUTING DOC FOR COLLABO WEB APP
---

# ℹ Contribute to Collabo Web App

***

_Number of projects:_ 2

_Languages or tools:_ Javascript, Typescript, Node Js, Express Js, MongoDB, Reactjs, Nextjs, Figma

***

_**Description:**_ The Code Collabo Web app has 2 projects inside it:

* Frontend client: The Frontend client is the User Interface of the Collabo Web app. The client interacts with the back-end server of the Collabo Web app.
* Server: The server API is the back-end (or server-side) of the Collabo web app. It contains the API calls used by the front-end client of the Collabo Web app.

***

_**Local development instructions:**_

* Cloning and developing locally on your computer: Visit the _**Project and Git Workflow**_ section from the _**Contribution Workflow**_ page. General guidance for how to clone and work with our repositories (depending on what type of contributor you are) exists there.
* Repository URL (this will come in handy when following the _**Project and Git Workflow**_ instructions): [https://github.com/code-collabo/collabo-web-app](https://github.com/code-collabo/collabo-web-app)
* Once you have the repository on your local computer, see the tabs below for other instructions, depending on the Collabo Web App project you want to run.

{% tabs %}
{% tab title="Frontend Client" %}
_**Instructions for installing dependencies and starting the frontend client:**_

* Change directory into the `client` folder of the repository
* Once in the `client` folder, follow the steps below

Install dependencies:

```
npm install
```

Run the development server:

```
npm run dev
```
{% endtab %}

{% tab title="Backend Server API" %}
_**Instructions for installing dependencies and starting the backend server API:**_

* Change directory into the `server` folder of the repository
* Once in the `server` folder, follow _**steps 1 to 4**_ in the tabs under the [Running the generated backend API application](https://code-collabo.gitbook.io/node-mongo-user/node-mongo-user-docs/readme#running-the-generated-backend-api-application) section of the node-mongo user docs, depending on the connection setup type you prefer to use.
{% endtab %}
{% endtabs %}

***

_**Issues and issue tickets:**_

* Finding issues: While you can find all Collabo Web app issues at this URL [https://github.com/code-collabo/collabo-web-app/issues](https://github.com/code-collabo/collabo-web-app/issues), we recommend that you follow the general guide for finding issues in the _**How and Where to report issues**_ section, which can be found somewhere in the _**Contribution Workflow**_.
* Reporting issues: We recommend that you follow the general guide for reporting issues in the _**How to find tasks or issues to work on**_ section, which can be found somewhere in the _**Contribution Workflow**_. Submitting the issues you detect this way will help us to sort them, and send them to the appropriate project board for you and other contributors to work on them.
