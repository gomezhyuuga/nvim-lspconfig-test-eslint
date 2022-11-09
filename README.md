# nvim-lspconfig-eslint tests

This repo is to check that the default configuration from nvim-lspconfig
works on eslint-based projects.


```
.
├── project-eslint-eslintrc
├── project-eslint-packagejson
├── project-noeslint
```

`project-eslint-eslintpackagejson`: uses eslint with config in `package.json`; LSP should be started.

`project-eslint-eslintrcjs`: uses eslint with config in `.eslintrc`; LSP should be started.

`project-eslint-eslint*`: ... same as others above, LSP should be started.

`project-noeslint`: doesn't use eslint at all, no LSP should be started.
