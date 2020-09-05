# Zi-Shane's Blog

## How to update post
```
# 1. Perform a site build and output to 'public/' directory.
> hugo

# 2-4.
> cd public
> git add .
> git commit -m "first build"

# 5. Return to the project root.
> cd ../

# 6-7.
> git add .
> git commit -m "first build - update submodule reference"

# 8. Push the source project *and* the public submodule to Github together.
> git push -u origin master --recurse-submodules=on-demand
```
