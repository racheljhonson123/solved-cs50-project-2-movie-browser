Download Link: https://assignmentchef.com/product/solved-cs50-project-2-movie-browser
<br>
Movie BrowserFor this project, you’ll be implementing a movie browser. It will allow users tosearch for movies included in the [Open Movie Database](http://www.omdbapi.com/)and view additional information about any movies they select. Check out the[staff solution](#staff-solution) for a working version.

## Requirements– You may not import libraries other than the below:– `expo`– `react`– `react-native`– `prop-types`– `react-navigation`– Any library for icons– There should be at least one `StackNavigator`– There should be a search screen that allows users to search for movies– You should show more than 10 results if more than 10 results exist– There should be a screen that shows additional information about a selected movie

The aesthetics of the app are up to you!

### Challenge (Not Required)– Coming soon!

## Getting StartedFirst, head to [this link](https://docs.expo.io/versions/latest/get-started/installation/)to install Expo. You’ll need the XDE for your computer and the mobile client(Expo app) on your phone. If you prefer, you can also install the iOS simulator(Macs only) and/or the Android emulator.

You’ll also need Node.js and NPM installed. You can check if you already have theminstalled by opening a terminal and running `node –version` and `npm –version`.If numbers are printed, you’re good to go. If not, [install them](https://nodejs.org/en/).You’ll probably want the LTS version (v8.x.x). NPM will be installed automaticallywhen you install node.

After installing those software dependencies, you’ll need to install your app’s“dependencies” (libraries that are required to run the app, such as `react`,`react-native`, etc.). Fortunately, it’s very easy to do! From a terminal, `cd`into this directory and run the command `npm install`. NPM will look at the[`package.json`](/package.json) file’s `dependencies` key and install thoselibraries, as well as all of those libraries’ dependencies (and the dependencies’dependencies and so on).

Now you have everything installed that you need to run the app! Open the ExpoXDE app and click the `Open existing project…` button. Select the folder thatcontains this file (make sure you have the parent folder and not this file) andpress `Open`.

You should now see two panels with logs. The left will output some messeages,hopefully including `Dependency graph loaded.`. If you see this message, thenyour app is running (well technically the bundler that serves your app is running).

You can now open the app on your phone or simulator by clicking one of the buttonsin the top right. To open on your phone, click the `Share` button and scan theQR code from the Expo app on your phone. To open in a simulator, click the `Device`button and select the simulator into which you want to open your app.

When you have the app open in your phone or simulator, try opening [`App.js`](/App.js)and changing a line. You should see it update on your phone!

If you want to get started before we talk about data fetching in the next lecture,you can use the mock data defined in [`mockData.js`](./mockData.js).