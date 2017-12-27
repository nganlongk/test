Microsoft Windows [Version 10.0.16299.125]
(c) 2017 Microsoft Corporation. All rights reserved.

C:\Users\KamSuen>node -v
v8.9.3

C:\Users\KamSuen>cd project

C:\Users\KamSuen\Project>test
'test' is not recognized as an internal or external command,
operable program or batch file.

C:\Users\KamSuen\Project>cd test

C:\Users\KamSuen\Project\test>node router.js
module.js:538
    throw err;
    ^

Error: Cannot find module 'C:\Users\KamSuen\Project\test\router.js'
    at Function.Module._resolveFilename (module.js:536:15)
    at Function.Module._load (module.js:466:25)
    at Function.Module.runMain (module.js:676:10)
    at startup (bootstrap_node.js:187:16)
    at bootstrap_node.js:608:3
