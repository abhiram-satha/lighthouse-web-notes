# Process Argv

- build in object that will loop through the command:

```javascript
  process.argv
```

`node processfile.js` tom jack 43

```javascript
for (let j = 0; j < process.argv.length; j++) {
    console.log(j + ' -> ' + (process.argv[j]));
}

```

will return the following: 


0 -> /Users/scott/.nvm/versions/node/v4.8.0/bin/node

1 -> /Users/scott/javascript/processargv.js

2 -> tom

3 -> jack

4 -> 43
