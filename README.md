# Template: About Me Demo

This is a template repository that implements a very simple HTML page. It is intended to demonstrate the minimum requirements to create a website, modify and serve it locally, and deploy it.

# Install Dependencies

There is a single dependency for this project - the Node `live-server` package. This simply serves the files at the root of the repository, and performs automatic reloads in the browser if a file changes.

```
npm install
```

# Run the server

```
npm start
```

# View in browser

Open your browser and type the development server URL into the address bar:

```
http://127.0.0.1:8080
```

# Make changes

1. Add some basic information about yourself to the `index.html`, removing text that is there as a placeholder
2. Add or modify styles in `index.css`
3. Add a simple piece of functionality to the page using Javascript, in the `index.js` file.

**Note** - Don't worry too much about mistakes or things that look silly. This exercise is just to ensure you have an overview of the basic moving parts.

## How-to

- [Basic HTML]()
- [Basic CSS]()
- [Basic JS]()

# Commit and push changes

Once you have made your changes to the HTML, CSS, and JS files, you need to perform two steps in order to get these changes in your hosted repository on GitHub.

Below, we are showing the command line interface. If you want to do this with a UI from VS Code (most people do), then, [get familiar with it here](https://code.visualstudio.com/docs/sourcecontrol/overview).

## git add

Tell git which files you want to *stage* for commiting.

```
git add <space seperated list of files>
```

e.g.:

```
git add index.html index.css index.js
```

## git commit

Commit your changes, including adding a commit message.

```
git commit -m "<insert description of your changes here>"
```

e.g.:

```
git commit -m "my about me information"
```

[Read more about git commit](https://www.atlassian.com/git/tutorials/saving-changes/git-commit)

## git push


```
git push origin main
```

[Read more about git push](https://www.atlassian.com/git/tutorials/syncing/git-push)
