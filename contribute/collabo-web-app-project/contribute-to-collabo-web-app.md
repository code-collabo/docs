---
description: CONTRIBUTING DOC FOR COLLABO WEB APP
---

# ℹ Contribute to Collabo Web App

***

_Number of projects:_ 3

_Languages or tools:_ Javascript, Typescript, Expressjs, MongoDB, Reactjs, Nextjs, Figma, Draw.io

_Issues:_ [https://github.com/code-collabo/web-app/issues](https://github.com/code-collabo/web-app/issues)

***

{% tabs %}
{% tab title="Server API Development" %}
_**Repository URL:**_ [https://github.com/code-collabo/web-app](https://github.com/code-collabo/web-app)

***

The server API is the back-end (or server-side) of the Code Collabo web application. It contains the API calls used by the front-end (client-side).

Ensure to clone (and fork) based on the instruction in the contributing guide (depending on your role) before commencing contribution.

***

**START SERVER API**

_**Connection Option 1 (MongoDB ATLAS)**_

**Step 1**

change directory into the server folder

**Step 2**

Install dependencies:

```sh
npm install
```

**Step 3**

* Ensure you have internet connection
* Have a monogDB atlas cluster set up in the cloud
* Get your atlas mongoDB uri string

**Step 4**

* Rename the `.env.example` file to `.env`
* Change `PORT_ATLAS` environment variable to your preferred port number in the .env file
* Add your atlas mongoDB uri string to the `MONGODB_ATLAS_URI` environment variable in the .env file

**Step 5**

Start the automated development server and choose ATLAS connection:

```sh
npm run dev
```

**Step 5 (alternative)**

You can also use the (manual) development server alternative for connection to mongoDB atlas:

```sh
npm run dev:atlas
```



**Connection option 2: Running the development server (mongoDB local)**

**Step 1**

change directory into the server folder

**Step 2**

Install dependencies:

```sh
npm install
```

**Step 3**

* Have mongoDB installed and running on your computer
* Get your local mongoDB uri string

**Step 4**

* Rename the `.env.example` file to `.env`
* Change `PORT_LOCAL` environment variable to your preferred port number in the .env file
* Add your local mongoDB uri string to the `MONGODB_LOCAL_URI` environment variable in the .env file

**Step 5**

Start the automated development server and choose LOCAL connection:

```sh
npm run dev
```

**Step 6 (alternative)**

You can also use the (manual) development server alternative for connection to local mongoDB:

{% code fullWidth="false" %}
```sh
npm run dev:local
```
{% endcode %}
{% endtab %}

{% tab title="Client Development" %}
{% hint style="info" %}


No documentation is available yet, check back later.
{% endhint %}
{% endtab %}
{% endtabs %}





