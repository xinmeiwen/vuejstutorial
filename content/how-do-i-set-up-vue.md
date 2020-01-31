+++
author = "Frank"
date = 2020-01-30T16:02:00Z
featured = false
image = "/uploads/VUED.jpg"
keywords = []
tags = []
title = "How do I set up Vue?"
url = ""

+++
VueJS is one of the best frameworks for JavaScript like ReactJS. The VueJS is used to design the user interface layer, it is easy to pick up for any developers. It is compatible with other libraries and extensions as well. If you want to create a single page application then VueJS is the first choice in my opinion. In the development filed there may be so many issues that can not be solved by using a single library, so the VueJS is compatible with other libraries so you can easily go for it. The VueJS is supported by all popular browsers like Chrome, Firefox, IE, Safari, etc. You can easily compare this library with your favorite libraries.

# **Installation of VueJS:**

The VueJs can be used in three different ways those are listed below:

* Directly included CDN file.
* Install through the npm.
* By CLI use VueJS

**Directly include CDN file:** You need to download the VueJS **Development Version** and **Production Version** then include it in the script tag.

**CDN:**

1. For learning purpose, you can use below script(with the specific version):

`<script src=”https://cdn.jsdelivr.net/npm/vue/dist/vue.js”></script>`


2\. For production purpose, you can use below script:


`<script src=”https://cdn.jsdelivr.net/npm/vue@2.6.11″></script>`


3\. For ES modules compatible, use below script:

> _<script type=”module”>  
> import Vue from ‘https://cdn.jsdelivr.net/npm/vue@2.6.11/dist/vue.esm.browser.js’  
> </script>_

# **Install through the npm:**

Before applying this procedure you must have installed npm, to check npm installed or not run the below command:

    npm -v

Now you are ready to install the VueJS, to do so run the below command. It will install the most updated stable version of VueJS.

    npm install vue

![](/uploads/Screenshot-from-2020-01-19-00-26-44.png)

# **By CLI use VueJS:**

Open your terminal or command prompt and run the below command.

    npm install --global vue-cli

![](/uploads/Screenshot-from-2020-01-19-00-37-59.png)

# **Let’s create a project through webpack:**

* **Step 1:** Run the below command to create the project.

      vue init webpack myproject

  ![](/uploads/Screenshot-from-2020-01-19-00-44-33.png)
* **Step 2:** Now get into the myproject folder by using below command.

      cd myproject
* **Step 3:** Run the below command to run locally your project.

      npm run dev

  ![](/uploads/Screenshot-from-2020-01-19-00-58-58.png)
* **Note:** If the third step does not work then run **npm install** command and hit the third step again again.  
  The project structure will look like below image:  
  ![](/uploads/Screenshot-from-2020-01-19-00-54-28.png)