# Mutable File System examples

The MFS is a file system abstraction built on top of IPFS.  It supports all the operations you would expect such as creating directories, adding files to them, renaming, coping, deleting, etc.

## Running the demo

In this directory:

```
$ npm install
$ npm start
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
