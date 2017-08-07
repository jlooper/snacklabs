# Snacklab Components

A set of Polymer elements, based on the Google Codelabs platform.

## Development setup

CD to the root of the project and `bower install` to get all dependencies. 

To run the project locally, you need polyserve: 
[polyserve](https://github.com/PolymerLabs/polyserve):
`npm install -g polyserve`.

Fire up the server with `polyserve` command and point your browser to:

    http://localhost:8080

Or to where the terminal guides you.

## How to create a new Snacklab

You can create your own Snacklabs, and after approval, they will be linked from NativeScriptSnacks.com. To create a new Snacklab:

- Add a folder referencing the content of your tutorial, including an `index.html` and `snacklab-elements.html` file, in the `snacklabs` folder. 
- Add step elements to your Snacklab by creating step pages in this folder, named appropriately. 
- Add those pages as well to your folder's `snacklab-elements.html` file so that they are properly imported. 
- Add the steps as well to your folder's `index.html` file, as per the flexbox example.
- Your Snacklab should have a linkable URL such as `<url>/snacklabs/flexbox` by the end of your development.

