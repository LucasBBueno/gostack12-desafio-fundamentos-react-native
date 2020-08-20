<h1 align="center">
     <img height="50" style="border-radius: 10px 0 10px" src="https://res.cloudinary.com/lucasbbueno/image/upload/v1597880375/logo_3x_yewtkt.png">
</h1>

<h4 align="center">
  A React Native application for a marketplace system
</h4>

<p align="center">
  <a href="#memo-about">About project</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#rocket-technologies">Technologies</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;
  <a href="#rocket-technologies">Install</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;
  <a href="#rocket-technologies">Run</a>&nbsp;&nbsp;&nbsp;
</p>


<p align="center">
    <img height="550" src="https://res.cloudinary.com/lucasbbueno/image/upload/v1597880347/GoMarketPlaceMobile_csz4wp.gif">
</P>

## :memo: About

This project was developed during the GoStack 12 bootcamp offered by Rocketseat and it's an eighth challenge for use context api and Async storage in React Native

Two screens were created, the first being a Dashboard screen with a products list that can be added to a cart and in the bottom the balance of it. In the second screen we can view the cart balance too, and increment or decrement products.

With this development, it was possible to put into practice the use of context api in React Native and also the async storage.

Thanks to [Rocketseat](https://rocketseat.com.br/) to proprose this activity.


## :rocket: Technologies

The main technologies used were:

- [React Native](https://reactnative.dev/)
- [TypeScript](https://www.typescriptlang.org/docs/home.html)
- [Async-storage](https://github.com/react-native-community/async-storage)
- [Context](https://pt-br.reactjs.org/docs/context.html)
- [Axios](https://github.com/axios/axios)
- [styled-components](https://styled-components.com/docs)
- [Yarn](https://yarnpkg.com/)
- [VS Code](https://code.visualstudio.com/)


## :floppy_disk: Install
To install this application and download the dependencies with [Yarn](https://yarnpkg.com/) we can use:
```bash
$ git clone https://github.com/LucasBBueno/gostack12-desafio-fundamentos-react-native
$ cd gostack12-desafio-fundamentos-react-native
$ yarn
```

## :cd: Run
We'll execute this application in android emulator. For a physical android device is needed to change the baseURL in **api.ts** file to your machine ip.

Other thing that was used an 'fake api' with json server to provide products. In that case, we can run the api with:

```bash
$ yarn json-server server.json -p 3333
```

Now we can execute the application with:

```bash
$ yarn android
```

---


Made with :heart: by Lucas Bueno :wave: [Get in touch!](https://www.linkedin.com/in/lucasbbueno).
