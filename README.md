angular-local-storage
=====================

An Angular module that gives you access to the browsers local storage, forked to be used in https://github.com/destegabry/angular-requirejs-html5boilerplate-seed

Remember to set your app name (prefix) in the settings at the beginning of localStorageModule.js.

To do:
- Add tests
- Expand Readme

Example use: 

```javascript
    // Start fresh
    localStorageService.clearAll();
    localStorageService.add('Favorite Sport','Ultimate Frisbee');
```
Check out the full demo and documentation at http://gregpike.net/demos/angular-local-storage/demo.html