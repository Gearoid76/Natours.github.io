# Natours project 
This is one of three project from the Advanced CSS project folder from Udemy by Jonas Schmedtmann,
currently in progress, keep visiting to see the end product.
I have also deleted the node_modules folder so. one has to run npm i (to reinstall the folder) in the command prompt
To access this, as a developer, one has to open two command prompts and write: npm run compile:sass
and in the second: live-server
This works in situ. But if you do download to edit it you need the modules folder.

Since this is the end of the lecture by Jonas Schmedtmann the lines 5 - 6 have been replaced by the 
npm run start "start": "npm-run-all --parallel devserver watch:sass", which will run both the dev server and live-server in parallel, so no need to have two seperate command lines. 

As for the Build process this is now npm run build:css for production. please note that i have commented out line 9 in index.html which relates  <link rel="stylesheet" href="css/icon-font.css">  now not needed after developemnt or on a live server.
