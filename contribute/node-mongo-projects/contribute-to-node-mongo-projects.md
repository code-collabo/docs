---
description: CONTRIBUTING DOC FOR NODE MONGO PROJECTS
---

# ℹ Contribute to Node Mongo Projects

***

{% hint style="info" %}
_User Doc:_ [https://code-collabo.gitbook.io/node-mongo-user/node-mongo-user-docs/readme](https://code-collabo.gitbook.io/node-mongo-user/node-mongo-user-docs/readme)
{% endhint %}

***

_Number of projects:_ 3

_Languages or tools:_ Javascript, Typescript, Node Js, MongoDB

_Issues:_ [https://github.com/code-collabo/node-mongo/issues](https://github.com/code-collabo/node-mongo/issues)

***

{% tabs %}
{% tab title="CLI" %}
_**Repository:**_ [https://github.com/code-collabo/node-mongo-cli](https://github.com/code-collabo/node-mongo-cli)

***

The node-mongo commands and flags for the node-mongo CLI are the same as what is in the user doc.

***

However, the method of installation is different during code development. Change directory into the root of the CLI repository, after cloning the repository locally to your computer (don't forget to create a new branch from develop before adding and pushing your changes)  - see the _**Contribution Workflow**_ page for detailed workflow info. Install globally and uninstall globally in this manner during code development:

1. Install dependencies

```
npm install
```

2. Link after installing dependencies:

```
npm link
```

3. Unlink (for when you are done developing):

```
npm unlink
```

***

#### Learning resources

* [Twilio | Dominik Kundel: How to build a CLI with node.js](https://youtu.be/s2h28p4s-Xs) - _YouTube video_.
* [Twilio | Dominik Kundel: How to build a CLI with node.js](https://www.twilio.com/blog/how-to-build-a-cli-with-node-js) _- blog post._
{% endtab %}

{% tab title="API Boilerplate Template" %}
_**Repository:**_ [https://github.com/code-collabo/node-mongo-api-boilerplate-templates](https://github.com/code-collabo/node-mongo-api-boilerplate-templates)

***

Clone the repository locally on your computer (don't forget to create a new branch from develop before adding and pushing your changes) - see the _**Contribution Workflow**_ page for detailed workflow info. Change directory into the root of the API boilerplate template repository, and run the same npm scripts mentioned in the user doc i.e. npm install, npm run dev:atlas, npm run dev:local, etc.

***

How to handle the `.env` files are different during code development:

* Retain the `.env.example` file so that it doesn't get deleted from our repo when you submit your code fix
* Create a copy of the `.env.example` file, rename this copy to `.env` , then change the `PORT` and add other environment variables to store your secrets as desired in your `.env` file.

***

#### Learning resources

* [TomDoesTech: REST API with Node.js, Express, TypeScript, MongoDB & Zod](https://www.youtube.com/watch?v=BWUi6BS9T5Y).
* [TomDoesTech: Module '"mongoose"' has no exported member 'DocumentDefinition'.ts (tutorial fixes)](https://www.youtube.com/watch?v=5-1KuU-21uI).
* [Academind: Building a restful API with node.js](https://academind.com/tutorials/building-a-restful-api-with-nodejs/).
* [CodAffection: MEAN stack CRUD operations](https://youtu.be/UYh6EvpQquw) - _1st 33 minutes_.
{% endtab %}

{% tab title="Scripts" %}
_**Repository:**_ [https://github.com/code-collabo/node-mongo-scripts](https://github.com/code-collabo/node-mongo-scripts)

***

{% hint style="info" %}
Contributing doc is not yet available for node-mongo scripts.
{% endhint %}
{% endtab %}
{% endtabs %}
