### Install mongoose
Type into the terminal
```
npm i mongoose
```

### Install nodemon
Type into the terminal
```
npm i --save-dev nodemon
```

### Add nodemon in scripts, in package.json
scripts should look like the following
```
    "scripts": {
    "devStart": "nodemon script.js"
  },
```

### run the following in terminal - "devStart"
```
    npm run devStart
```
This will run the code in script.js

### import the mongoose library
```
    const mongoose = require('mongoose');
```

### Connect to mongodb
```
    mongoose.connect("mongodb://localhost/testdb");
```