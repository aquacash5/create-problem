# Create problem

This repo is to demonstrate a problem with `npm create`.

When executing `npm create @problem` from the root of the workspace, everything works fine.
However, executing the command in `./cloudflare` causes the following error:

```shell
npm ERR! code E404
npm ERR! 404 Not Found - GET https://registry.npmjs.org/@problem%2fcreate - Not found
npm ERR! 404 
npm ERR! 404  '@problem/create@*' is not in this registry.
npm ERR! 404 
npm ERR! 404 Note that you can also install from a
npm ERR! 404 tarball, folder, http url, or git url.

npm ERR! A complete log of this run can be found in: ...
```

The expected result is create template project is run in the current directory. Thus adding a project next to the `hello-world` project.
