## React-Electron-Template

Following is a template repository for creating a desktop based application combining React and Electron

Update all the react-based-code in `src/react/`
Once done, 3 simple commands to produce a linux based desktop app executable

```
 npm run build
 npm run build-electron
 npm run package
```

### To test in Development:
Run `npm run start` in 1 terminal to start react development server. 
Then in a different instance of terminal, run `npm run start-electron` to see the react-content in an electron window.

### Note:
Additional configuration and change in script required for `npm run package` for making a desktop app executable for Windows/Mac

### Reference:
https://medium.com/@johndyer24/building-a-production-electron-create-react-app-application-with-shared-code-using-electron-builder-c1f70f0e2649

Shoutout to guys who did everything in **create-react-app** and **electron**.
