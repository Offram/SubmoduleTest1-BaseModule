# Tutorial
https://www.vogella.com/tutorials/GitSubmodules/article.html#:~:text=Use%20the%20git%20submodule%20update,updates%20of%20the%20nested%20submodules.

# Basic Commands

## Initiate
```
git submodule add -b main https://github.com/Offram/SubmoduleTest1-SubModule.git
git submodule init
```

## Clone
```
git clone --recursive [URL to Git repo]
```

## Update
```
git submodule update --remote
```