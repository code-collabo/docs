---
description: CONTRIBUTING DOC FOR NODE MONGO PROJECTS
---

# ℹ Contribute to Node Mongo Projects

***

_Number of projects:_ 3

_Languages or tools:_ Javascript, Typescript, Node Js, Express Js, MongoDB

***

_**Description:**_ The Node Mongo project has 3 projects under it:

* CLI: The CLI helps to generate the API boilerplate templates.
* API boilerplate templates: The API boilerplate templates are and can be used to build new backend applications.
* Scripts: The scripts project repo contains code shared by the CLI and API boilerplate templates. It also contains code for the automated dev server used within the API boilerplate templates.

***

_**Local development instructions:**_

Find the local development instructions for the different Node Mongo projects in the tabs below, depending on the one you which to develop locally.

{% tabs %}
{% tab title="CLI" %}
_**Local development instructions:**_

* Cloning and developing locally on your computer: Visit the _**Project and Git Workflow**_ section from the _**Contribution Workflow**_ page. General guidance for how to clone and work with our repositories (depending on what type of contributor you are) exists there.
* Repository URL (this will come in handy when following the _**Project and Git Workflow**_ instructions): [https://github.com/code-collabo/node-mongo-cli](https://github.com/code-collabo/node-mongo-cli)
* Once you have the repository on your local computer, follow the installation instructions below.

***

_**Instructions for installing dependencies and linking CLI:**_

* Change directory into the root of the repository
* Once in the root of the repository, install globally and uninstall globally following the steps below

Install dependencies:

```
npm install
```

Link after installing dependencies:

```
npm link
```

Unlink (this is for when you are done developing):

```
npm unlink
```

***

_**CLI commands and flags:**_

The commands and flags for the node-mongo CLI are the same as what is in the user doc: [https://code-collabo.gitbook.io/node-mongo-user/node-mongo-user-docs/detailed-guide](https://code-collabo.gitbook.io/node-mongo-user/node-mongo-user-docs/detailed-guide)

***

#### Learning resources

* [Twilio | Dominik Kundel: How to build a CLI with node.js](https://youtu.be/s2h28p4s-Xs) - _YouTube video_.
* [Twilio | Dominik Kundel: How to build a CLI with node.js](https://www.twilio.com/blog/how-to-build-a-cli-with-node-js) _- blog post._
{% endtab %}

{% tab title="API Boilerplate Template" %}
_**Local development instructions:**_

* Cloning and developing locally on your computer: Visit the _**Project and Git Workflow**_ section from the _**Contribution Workflow**_ page. General guidance for how to clone and work with our repositories (depending on what type of contributor you are) exists there.
* Repository URL (this will come in handy when following the _**Project and Git Workflow**_ instructions): [https://github.com/code-collabo/node-mongo-api-boilerplate-templates](https://github.com/code-collabo/node-mongo-api-boilerplate-templates)
* Once you have the repository on your local computer, follow the installation instructions below.

***

_**Instructions for installing dependencies and starting the development server:**_

* Change directory into any of these folders in the repository, depending on the template you wish to work on: `ts` folder, `esm` folder or `cjs` folder.
* Once in the chosen folder, follow _**steps 1 to 4**_ in the tabs under the [Running the generated backend API application](https://code-collabo.gitbook.io/node-mongo-user/node-mongo-user-docs/readme#running-the-generated-backend-api-application) section of the node-mongo user docs, depending on the connection setup type you prefer to use.

***

_**Handling .env files during development:**_

* Retain the `.env.example` file so that it doesn't get deleted from our repo when you submit your code fix.
* Create a copy of the `.env.example` file, rename this copy to `.env` , then change the `PORT` and add other environment variables to store your secrets as desired or as needed in your `.env` file.

***

#### Learning resources

* [TomDoesTech: REST API with Node.js, Express, TypeScript, MongoDB & Zod](https://www.youtube.com/watch?v=BWUi6BS9T5Y).
* [TomDoesTech: Module '"mongoose"' has no exported member 'DocumentDefinition'.ts (tutorial fixes)](https://www.youtube.com/watch?v=5-1KuU-21uI).
* [Academind: Building a restful API with node.js](https://academind.com/tutorials/building-a-restful-api-with-nodejs/).
* [CodAffection: MEAN stack CRUD operations](https://youtu.be/UYh6EvpQquw) - _1st 33 minutes_.
{% endtab %}

{% tab title="Scripts" %}
_**Local development instructions:**_

* Cloning and developing locally on your computer: Visit the _**Project and Git Workflow**_ section from the _**Contribution Workflow**_ page. General guidance for how to clone and work with our repositories (depending on what type of contributor you are) exists there.
* Repository URL (this will come in handy when following the _**Project and Git Workflow**_ instructions): [https://github.com/code-collabo/node-mongo-scripts](https://github.com/code-collabo/node-mongo-scripts)
* Once you have the repository on your local computer, follow the installation instructions below.

***

_**Testing out the node-mongo scripts in other Node Mongo projects:**_

Follow these steps when developing and testing out the Node Mongo scripts inside the CLI or the API boilerplate template:

* Ensure you have the Mode Mongo project you want to test locally on your computer, you have completed their local development instructions, you have installed dependencies, and are able to run them - see the CLI and API boilerplate template tabs.
* Go to the `node_modules` folder within that Node Mongo project, you will find the `@code-collabo/node-mongo-scripts` folder. The reason you are able to find and access the scripts folder from that Node Mongo project `node_modules` is that `@code-collabo/node-mongo-scripts` was installed alongside other dependencies when you used the `npm install` script command (you can check the package.json file for that Node Mongo project to see that `@code-collabo/node-mongo-scripts` is present among the package dependencies).
* The `@code-collabo/node-mongo-scripts` folder inside the project's `node_modules` becomes your workspace. Make your changes in there as needed. Then in the chosen Node Mongo project, check your changes for existing functions or modules or import the functions or modules as needed before checking in the case of new functions/modules added.
* Once you are satisfied with your changes, copy the entire content of  `@code-collabo/node-mongo-scripts` where you made the changes (i.e. the one within the project's `node_modules` folder). Paste them into the node-mongo-scripts repository that you cloned earlier. Add and commit your changes in the cloned repository and send a pull request.

> The problem with this method is that git does not track the changes made from within the `node_modules` folder. This is particularly stressful/painful if you are making changes to many files. This is the reason why the instruction says to copy the entire content when done, so that you don't have to worry about remembering where you made the changes by yourself when you are ready to copy. But if the portion you changed is small and easy to remember, you can just copy and paste that small portion.

***

{% hint style="info" %}
Note: Only the API boilerplate template uses the node-mongo-script at the moment. Work is ongoing to add it to the CLI too.
{% endhint %}
{% endtab %}
{% endtabs %}

***

_**Issues and issue tickets:**_

* Finding issues: While you can find all Node Mongo project issues at this URL [https://github.com/code-collabo/node-mongo/issues](https://github.com/code-collabo/node-mongo/issues), we recommend that you follow the general guide for finding issues in the _**How and Where to report issues**_ section, which can be found somewhere in the _**Contribution Workflow**_.
* Reporting issues: We recommend that you follow the general guide for reporting issues in the _**How to find tasks or issues to work on**_ section, which can be found somewhere in the _**Contribution Workflow**_. Submitting the issues you detect this way will help us to sort them, and send them to the appropriate project board for you and other contributors to work on them.
