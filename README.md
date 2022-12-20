# Tasks App With React Hooks

This application belongs to the set of tutorials made with [React Hooks](https://es.reactjs.org/docs/hooks-intro.html).

This app creates task cards with their title, description, and a delete button via a form.

![Task App With React Hooks](https://i.ibb.co/9pnHxRJ/task-app-react-hooks.png")

This application clearly shows the use of **useState**, **useEffect** and **useContext** Hooks. It contains three components in addition to the parent App Component. Then we create a Context that contains the state of these three components which they access to extract information necessary for their functionality.

I use [Vite + React](https://vitejs.dev/guide/) to create the project. To style it I use the [TailwinCSS](https://tailwindcss.com/docs/guides/vite) library.


## Quick start

You should first install the node_modules package using:
```bash
npm install
```

To run the app open a terminal and run:
```bash
npm run dev
```

This will launch the web at the address:

http://localhost:5173/

## Compile dist files

To compile the dist files you need Node.js/npm, clone/download the repo then:

1. `npm install` (install npm deps)
2. _Optional:_ `npm run dev` (developer mode, autocompile with browsersync support for live demo)
3. `npm run production` (compile css/js files)

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).