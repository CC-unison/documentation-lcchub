---
layout: default
title: installation guide
parent: Tutorials
---

# Installation guide

Most of the hard work is handled by popular tools, the following installation guide
contains the necessary tools. lcc-hub was developed using a unix os (ubuntu) but running it
in other os should not be that different.

## Steps

### **1. Install a node version manager `NVM`**

Follow the official [instructions](https://github.com/nvm-sh/nvm)
to install `NVM` to manage two programs: `nodejs, npm`.

`js` code was originally supposed to be run in browsers. Browsers are programs to navigate the
internet (request files to other computers), and display content (files like: `HTML, CSS, JS`).
`nodejs` is a program that extracts the browser javascript engine (`Chrome V8 engine`) and
makes it suitable to be run by itself, allowing us to run `js` outside of a browser.

`npm` is a popular package manager that allow us to download `js` code
made from others so we don't have to reinvent the wheel.

Since there are many `nodejs` and `npm` versions, we use a program that allowFollow the official [instructions](https://github.com/nvm-sh/nvm)
to install `NVM` to manage two programs: `nodejs, npm`.

`js` code was originally supposed to be run in browsers. Browsers are programs to navigate the
internet (request files to other computers), and display content (files like: `HTML, CSS, JS`).
`nodejs` is a program that extracts the browser javascript engine (`Chrome V8 engine`) and
makes it suitable to be run by itself, that way we can use `js` that run in our desktops without
using a browser.

`npm` enable us to download `js` code made from others so we don't have to reinvent
the wheel.

Since there are many `nodejs` and `npm` versions, we use a program that enable
us to install and use different versions easily.

Check your installation using a terminal:

us to install and use different versions easily.

Check your installation using a terminal:

```bash
nvm -v             # 0.39.5 for me
nvm install 21.5.0 # v21.5.0 is already installed.
nvm use 21.5.0     # it's the default for me so I don't have to run this every time
node -v            # v21.5.0
npm -v             # v10.2.4
```

### **2. Install the repository**

```bash
git clone https://github.com/CC-unison/React-LCC-HUB.git
```

### **3. Install the dependencies**

```bash
cd React-LCC-HUB
npm install
```

`npm` will create a folder called `node_modules` that contains libraries/modules required to
run de project (also called dependencies).

### **4. Run the development server**

```bash
npm run dev
```

Open the localhost port with your browser to see the results.
If there are errors, go to the next step.

### 5. Add the `.env.local` file to the project

There are API keys that we don't share through the code, ask for the .env.local and
put it in the project directory.
