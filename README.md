# Ionic Visual Studio Starter Kit

This project is a fork from <https://github.com/bwhittington/IonicVisualStudioStarter>  
updated to Ionic 3.9.2 Angular 5.0

## Usage - When you want to use Visual Studio 2017 and TFS version control

1. Clone the project
2. Test the project from CLI > ionic serve
2. Delete the .GIT folder
3. Open the .sln
4. When asked to add Typescript@2.3 answer `no`, since ng 5.0 uses 2.4.2 and up to 2.5.0.  
`2.4.2` is already included in the package.json.
5. Test the project from VS (using Android Simulator): `F5`
6. Checkin to TFS

## Alternative

1. Follow this little procedure: <https://stackoverflow.com/a/46773321>

## Credits

Thanks to Brett The Whitt for the template and the tutorial
<https://github.com/bwhittington/IonicVisualStudioStarter>

--------------------------------

# Ionic Visual Studio Starter Kit
This project is just a starter kit for blank Ionic 3 project in Visual Studio 2017.  All I have done is updated all of the references needed for the blank template and verified they would run in debug mode.  This project has been updated to run under Ionic 3.6.0  You can find more about Ionic 3 and how to get it running in Visual Studio by following my blog post @ https://brettthewhitt.com/2017/05/18/ionic-package-and-ionic-3-setup-tutorial/
