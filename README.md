"RGR.js"

====babel-node server.js fails
make sure no other server running
run - npm install --save-dev babel-core
npm install --save-dev babel-preset-es2015
create a file - .babelrc  with content
{
  "presets": ["es2015"]
}
