Code from https://kinsta.com/blog/wordpress-react/
How To Create a Headless WordPress Site With React.js  (kinsta.com)

uses React and Vite:
 

npm create vite@latest my-blog-app 

cd my-blog-app 

npm install

npm install axios

... make code changes

npm run dev 

====
To do: add pagination: (+ this.state.page) returns page number on get request
"http://headless-wordpress-website.local/wp-json/wp/v2/posts?page=" + this.state.page

======================================================
# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh
