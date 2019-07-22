start a new monorepo
lerna init

create package
lerna create [name_of_package]

to build all the packages
lerna run tsc

to add dependency to all the packages
lerna add [module_name]

to add dependency to single package
lerna add [module_name] --scope=[package_name]

to set dependency of one package to other
lerna add [package_name] –-scope=[package_name]

to install dependencies
lerna bootstrap

for creating releases
lerna publish

to run npm scripts
lerna run
