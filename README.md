# ElectronApp

This project combines **Angular** and **Electron** to create a cross-platform _(currently only for Windows)_ desktop application. It was generated using [Angular CLI](https://github.com/angular/angular-cli) version 19.0.1.

## Table of Contents

- [Development](#development)
  - [Start the Development Server](#start-the-development-server)
  - [Run the Electron App](#run-the-electron-app)
- [Building](#building)
  - [Packaging the App](#packaging-the-app)
- [Additional Resources](#additional-resources)

---

## Development

### Start the Development Server

To start the Angular development server:

```bash
ng serve
```

Open your browser and navigate to http://localhost:4200/. The app will reload automatically when you modify any source files.

### Run the Electron App
To run the app in development mode with Electron:

```bash
npm run electron:serve
```

This command:

Starts the Angular development server on http://localhost:4200.
Launches the Electron app, loading the Angular app in a desktop environment.

## Building

### Packaging the App
To package the application into an executable for Windows run:

```bash
npm run build:win
```

The executable for Windows will be created in dist directory with filename of **Electron Angular App-v1.0.0-setup.exe**.
You can run this executable to install the application on Windows machine.


## Additional Resources
1. [Angular CLI Documentation](https://angular.dev/tools/cli)
2. [Electron Documentation](https://www.electronjs.org/docs/latest/)
3. [Electron Builder Documentation](https://www.electron.build/)