REPO NAME HERE
---
<pre>
/.circleci - CircleCI build script
/cmd - stand-alone executables
/docs - documentation
/internal - private packages
/service - API services for server/client interactions
</pre>

If using VSCode and the GoPls language server, you will need to opt-in to the `experimentalWorkspaceModule` option to properly reference and work with nested modules.

``` json
    # settings.json
    "gopls": {
        "experimentalWorkspaceModule": true,
    },
```