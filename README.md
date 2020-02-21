# Listing products in a catalogue using the Commerce.js SDK
The goal of this guide is to provide a basic walkthrough on how to list products in a catalog using the Commerce.js SDK.

Commerce.js SDK/CDN version used: v1 or v2

[Live Demo]()

### Requirements

- A code editor
- NodeJS
- npm or yarn

### Prerequisites

This guide is assuming some basic knowledge of the following:
- how to use Javascript
- what an API is and how/when to use it
- JS frameworks

### Setup

1. Register or sign in to your Chec account. 
Chec is the eCommerce infrastructure and platform the Commerce.js SDK is built upon to support a broad spectrum of merchants and use-cases.
- Sign up [here](https://dashboard.chec.io/signup) OR
- Create an account using the [CLI](https://github.com/chec/cli)
- After creating a Chec account, you will receive 2 sets of keys. These will be used when installing Commerce.js! The keys can be found in your Chec Dashboard in "Setup" under the "Developer" tab. Read more about their usages [here](https://commercejs.com/docs/overview/getting-started.html).

2. Upload products
- In order to list your products, you need to upload them first!
- Upload products under the "Products" tab in your Chec Dashboard. Click on the + sign or "Add Product" to add more products of your choice.


### Installing Commerce.js

Use our Commerce.js SDK to access the Chec API data from your application. Installing Commerce.js will require using either your "Public Key" or "Sandbox Public Key". As mentioned in step 2 of setup, read more about their usages [here](https://commercejs.com/docs/overview/getting-started.html).

*Choose either one of the installation methods:* 

1. Installing via CDN

```
<script type="text/javascript" src="https://assets.chec-cdn.com/v2/commerce.js"></script>
```

```
// The following line will create a new Commerce instance!
const commerce = new Commerce('{public_api_key}', true);
```

Adding true as the second constructor argument enables the Commerce.js console debugger.

2. Installing via NPM

In your project's root folder, type this command in your terminal:

```
npm install @chec/commerce.js
```
```
import Commerce from '@chec/commerce.js';
// The following line will create a new Commerce instance!
const commerce = new Commerce('{public_api_key}', true);4
```

### Project usage

A step by step series on injecting Commerce.js logic.

1. First step of injecting Commerce.js logic

```
example script
```

2. And repeat

```
example script
```

2. Until finished

```
example script
```

End with linking an example of live project or demo.
[Live Demo]()


## Built With

List all frameworks/tools used.

* [Vue.js](link) - The web framework used
* [TailwindCSS](link) - The web framework used
* [Yarn](link) - The web framework used

## Authors

* **Name** - [Github](https://github.com/chec)

See also the list of [contributors](https://github.com/your/project/contributors) who participated in this project.
