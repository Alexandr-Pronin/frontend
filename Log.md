-----> Building on the Heroku-20 stack
-----> Using buildpack: heroku/nodejs
-----> Node.js app detected
       
-----> Creating runtime environment
       
       NPM_CONFIG_LOGLEVEL=error
       NODE_VERBOSE=false
       NODE_ENV=production
       NODE_MODULES_CACHE=true
       
-----> Installing binaries
       engines.node (package.json):  unspecified
       engines.npm (package.json):   unspecified (use default)
       
       Resolving node version 14.x...
       Downloading and installing node 14.17.0...
       Using default npm version: 6.14.13
       
-----> Restoring cache
       - node_modules
       
-----> Installing dependencies
       Installing node modules (package.json)
       audited 1868 packages in 14.683s
       
       92 packages are looking for funding
         run `npm fund` for details
       
       found 83 vulnerabilities (80 moderate, 3 high)
         run `npm audit fix` to fix them, or `npm audit` for details
       
-----> Build
       Running build
       
       > web-frontend@1.0.0 build /tmp/build_b040efd6
       > react-scripts build
       
       Creating an optimized production build...
       Compiled with warnings.
       
       ./src/views/dashboard/protocolTemplates/labelEditor.tsx
         Line 103:5:  Do not mutate state directly. Use setState()  react/no-direct-mutation-state
       
       ./src/index.tsx
         Line 11:10:  'UserBuilder' is defined but never used  @typescript-eslint/no-unused-vars
       
       ./src/views/dashboard/entryViews/protocolEntryEditTableView.tsx
         Line 13:3:   'Fab' is defined but never used                         @typescript-eslint/no-unused-vars
         Line 124:9:  'addButtonDisabled' is assigned a value but never used  @typescript-eslint/no-unused-vars
         Line 204:5:  Nested block is redundant                               no-lone-blocks
         Line 227:5:  Nested block is redundant                               no-lone-blocks
       
       ./src/models/workee.ts
         Line 1:10:  'App' is defined but never used  @typescript-eslint/no-unused-vars
       
       ./src/views/dashboard/devicesView.tsx
         Line 23:10:  'QRCodeView' is defined but never used  @typescript-eslint/no-unused-vars
       
       ./src/views/dashboard/entryViews/protocolTableEntryView.tsx
         Line 2:10:  'render' is defined but never used  @typescript-eslint/no-unused-vars
       
       ./src/views/dashboard/qrCodeView.tsx
         Line 2:17:  'Grid' is defined but never used  @typescript-eslint/no-unused-vars
       
       ./src/parser/protocolParserV1.ts
         Line 34:9:   Expected an error object to be thrown         no-throw-literal
         Line 42:9:   Expected an error object to be thrown         no-throw-literal
         Line 51:9:   Expected an error object to be thrown         no-throw-literal
         Line 68:9:   Expected an error object to be thrown         no-throw-literal
         Line 75:71:  Expected an error object to be thrown         no-throw-literal
         Line 81:61:  Expected an error object to be thrown         no-throw-literal
         Line 87:39:  Expected to return a value in arrow function  array-callback-return
       
       ./src/views/dashboard/completedProtocols/completedArchivedProtocolsView.tsx
         Line 3:3:  'Paper' is defined but never used   @typescript-eslint/no-unused-vars
         Line 4:3:  'Button' is defined but never used  @typescript-eslint/no-unused-vars
       
       ./src/views/dashboard/completedProtocols/protocolDeleteDialog.tsx
         Line 41:56:  Expected to return a value in arrow function  array-callback-return
       
       ./src/views/dashboard/completedProtocols/completedProtocolsView.tsx
         Line 5:10:   'ProtocolParserV1' is defined but never used  @typescript-eslint/no-unused-vars
         Line 11:10:  'BackendService' is defined but never used    @typescript-eslint/no-unused-vars
         Line 12:8:   'axios' is defined but never used             @typescript-eslint/no-unused-vars
       
       ./src/views/dashboard/completedProtocols/completedProtocolView.tsx
         Line 5:3:  'CardActionArea' is defined but never used  @typescript-eslint/no-unused-vars
       
       ./src/views/dashboard/protocolTemplates/protocolTemplatesView.tsx
         Line 6:3:   'ExpansionPanel' is defined but never used         @typescript-eslint/no-unused-vars
         Line 7:3:   'ExpansionPanelSummary' is defined but never used  @typescript-eslint/no-unused-vars
         Line 10:3:  'FormControlLabel' is defined but never used       @typescript-eslint/no-unused-vars
         Line 20:8:  'ExpandMoreIcon' is defined but never used         @typescript-eslint/no-unused-vars
       
       ./src/views/login/loginPageView.tsx
         Line 6:8:   'axios' is defined but never used           @typescript-eslint/no-unused-vars
         Line 7:10:  'BackendService' is defined but never used  @typescript-eslint/no-unused-vars
       
       Search for the keywords to learn more about each warning.
       To ignore, add // eslint-disable-next-line to the line before.
       
       File sizes after gzip:
       
         824.18 KB  build/static/js/2.5b5f73e5.chunk.js
         53.85 KB   build/static/js/3.f0c45f94.chunk.js
         39.12 KB   build/static/js/5.264a9610.chunk.js
         17.18 KB   build/static/js/main.d403442f.chunk.js
         7.02 KB    build/static/js/4.995ec51c.chunk.js
         1.19 KB    build/static/js/runtime-main.25446b6d.js
       
       The project was built assuming it is hosted at /.
       You can control this with the homepage field in your package.json.
       
       The build folder is ready to be deployed.
       You may serve it with a static server:
       
         npm install -g serve
         serve -s build
       
       Find out more about deployment here:
       
         bit.ly/CRA-deploy
       
       
-----> Caching build
       - node_modules
       
-----> Pruning devDependencies
       audited 1868 packages in 13.626s
       
       92 packages are looking for funding
         run `npm fund` for details
       
       found 83 vulnerabilities (80 moderate, 3 high)
         run `npm audit fix` to fix them, or `npm audit` for details
       
-----> Build succeeded!
-----> Discovering process types
       Procfile declares types     -> (none)
       Default types for buildpack -> web
-----> Compressing...
       Done: 114.8M
-----> Launching...
       Released v6
       https://frontendbrille.herokuapp.com/ deployed to Heroku
