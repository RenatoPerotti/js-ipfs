# Mutable File System examples

The MFS is a file system abstraction built on top of IPFS.  It supports all the operations you would expect such as creating directories, adding files to them, renaming, coping, deleting, etc.

This demo allows you to upload files from your computer and use them to explore MFS methods from within your web browser.

![screenshot](screenshot_1.png)

![screenshot](screenshot_2.png)

## Running the demo

Fork and clone this repo.

Navigate into this directory:

```
$ cd js-ipfs/examples/browser-mfs
```

In this directory:

```
$ npm install     (don't be bothered by the WARNings)
$ npm start       (the first time you will have to do this twice)
```
```
Tips for your first try:
Make sure you download/clone the whole directory (green button in the root of this repository), the 'install command' may not only use files within the examples directory! :o
Than get started by file-exploring into the example directory you want to try, from there right click to open a terminal (command prompt).
Get access with administrative permissions (in Ubuntu: sudo -s), and you will need npm, gitt-all and Node.js installed globally.
Now type: npm install    This will read from the package.json file what needs to be downloaded, the files are usually put in a newly created directory called: node_modules
Now type: npm start   This will read from the package.json file what javascript code (usually the index.js in the src directory) needs to be executed by the Node.js program to  compile (meaning bundle to a compact version usually called bundle.js in directory: public).
The 'npm start' command will also start up a simple http server so you can see the content in your web browser (but just dragging the index.html in the browser also works fine)

```

Then open [http://localhost:8888](http://localhost:8888) in your browser.

## Hitchhiker's guide to IPFS

Just some help if this is your first trip to the File System.

Make sure you download/clone the repository as a whole (green button in the root of this repository), because the 'install' command may not only use just files within the examples directory, but also from the root! :o

After this get started by navigating into the example directory you want to try, from there right click to open a terminal (command prompt).
Get access with administrative permissions (in Ubuntu: sudo -s), and you will need npm, gitt-all and Node.js installed globally (sudo apt-get install nodejs). Next you will need to globally install 3 more dependancies (look at the readme of js-ipfs), node-gyp, python (2.7 - 3.7), make and GCC (npm install -g gcc)

Now type: npm install    This will read from the package.json file (should be present in the example directory where you are) for what dependencies are needed locally. The installations go in a newly created directory called: node_modules

Now type: npm start   This will read from the package.json file what javascript code (often the index.js in directory src) needs to be executed by the Node.js program to compile (meaning bundle all the used scripts together in a compact version usually called bundle.js often placed in directory public).

The 'npm start' command will often also start up a simple http server so you can see the content in your web browser (but IPFS is client-side so just dragging the index.html in the browser should also work).

If you want a bit more than notepad for editing your code, you can use sublimetext.com
