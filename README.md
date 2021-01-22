# [Zi-Shane's Blog](https://zi-shane.github.io/)

## How to update post
```bash=
# 1. Perform a site build and output to 'public/' directory.
hugo

# 2. commit public
cd public
git add .
git commit -m "first build"

# 3. commit hugo project
cd ../
git add .
git commit -m "first build - update submodule reference"

# 4. Push the source project *and* the public submodule to Github together.
git push -u origin master --recurse-submodules=on-demand
```

## How to update submodule
```
cd themes/hello-friend
git pull master
```

## clone this repo to new computer
```
git clone --recursive git@github.com:Zi-Shane/hugo-gh-pages-source.git

# Run below in root
npm install
npm i yarn
npx yarn
hugo
```
