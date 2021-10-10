

## basic: 
```yaml



nodeLinker: node-modules

plugins:
  - path: .yarn/plugins/@yarnpkg/plugin-workspace-tools.cjs
    spec: "@yarnpkg/plugin-workspace-tools"
  - path: .yarn/plugins/@yarnpkg/plugin-compat.cjs
    spec: "@yarnpkg/plugin-compat"

yarnPath: .yarn/releases/yarn-3.0.2.cjs

# install modules here
#--modules-folder apps/my_cool_application/static/
--modules-folder .

# Note: target directory goes after `--modules-folder` {{target dir}}
# NOte__arefin__oct_10: /home/arefin/Programs/byvl/rtk-oct-9-21/node_modules/

```
