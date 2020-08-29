# Basic Ostapoff template

CRA version <= 3.4.1 blacklists usage of `devDependencies` in `template.json`.
This template hacks this issue by adding `dev-Dependancies` instead of `devDependencies`,
please, rename this section in your application `package.json` after it is being created with this template.
