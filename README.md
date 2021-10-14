# What is this?
This project is the only sample to publish the npm module in a public place. It can log only a simple message on the console.  

## Usage
```
const hello = require('npm-helloooworld');
hello.helloworld();
```

## Expected result
```
Hello npm!
```

## Note
This development note says the following three things:  

### To publish the npm module
After creating an npm module, you can execute the following to publish it.  
```
npm login
npm init
npm publish
```

### Update only README file
If you want to update a README file only, you can execute the following.  
```
npm version patch
npm publish
```

### Depulicated npm module name
After executing the ```npm publish```, if you get the below message, the same name npm module may exit in npm public storage.  
```
You do not have permission to publish "npm-helloworld". Are you logged in as the correct user?
```