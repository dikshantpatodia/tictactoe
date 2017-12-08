# Tic-Tac-Toe

A React implementation of Tic Tac Toe.

## How to get started ?
In command line, write the following commands:
```sh
npm install -g create-react-app

create-react-app my-app
cd my-app/
npm start
```

Then open [http://localhost:3000/](http://localhost:3000/) to see your app.<br>
When you’re ready to deploy to production, create a bundle with `npm run build`.

### Get Started Immediately

You **don’t** need to install or configure tools like Webpack or Babel.<br>
They are preconfigured and hidden so that you can focus on the code.

**You’ll need to have Node >= 6 on your machine**.

### Creating an App

To create a new app, run:

```sh
create-react-app tic-tac-toe
cd tic-tac-toe
```

It will create a directory called `tic-tac-toe` inside the current folder.<br>
Inside that directory, it will generate the initial project structure and install the transitive dependencies:

```
tic-tac-toe
├── README.md
├── node_modules
├── package.json
├── .gitignore
├── public
│   └── favicon.ico
│   └── index.html
│   └── manifest.json
└── src
    └── App.css
    └── App.js
    └── App.test.js
    └── index.css
    └── index.js
    └── logo.svg
    └── registerServiceWorker.js
```

Probably you can `delete` all the files in the `./src` folder and add a new file called `index.js` and also create a folder for styles where you can write the styles for the `App`.

Since, the styles have been written in `scss`, so you also need to have a compiler to process it to `css`.
For doing that, you can also install `sass-loader` using npm, but it requires a bit of configuration. So, to keep it simple install [Sass compiler](http://sass-lang.com/install).

Command for compiling the `scss` file to `css`:
```sh
cd assets
sass --watch style.scss:style.css
```

Kindly, refer the code for better understanding of the `files` and `codes`

After doing all the above, the folder structure will look like:

```
tic-tac-toe
├── README.md
├── node_modules
├── package.json
├──  package-lock.json
├── public
│   └── favicon.png
│   └── index.html
│   └── manifest.json
└── src
    └── assets
        └── style.css
        └── style.css.map
        └── style.scss
    └── index.js
```

### `npm start`

Runs the app in development mode.
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will automatically reload if you make changes to the code.<br>
You will see the build errors and lint warnings in the console.

### `npm run build`

Builds the app for production to the `build` folder.
It correctly bundles React in production mode and optimizes the build for the best performance.

Your app is ready to be deployed.

##### Author
Dikshant Patodia. Find me [here](http://dikshantpatodia.in).



