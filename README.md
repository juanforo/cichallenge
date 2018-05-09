# Node.js CI Hello World

A simple Node.js app ready to run inside a container

## Local deployment

- Install node using the right installer for your OS (https://nodejs.org/en/download/). Make sure to install npm too!

- Run the following command to install the needed modules

```
npm install
```

- After that. You should be able to run the app using 

```
npm start
```

- You can run the tests in the same way

```
npm test
```

The project also includes a Dockerfile that will let you run the app inside a container. You just need to build 
an image and then deploy it.
