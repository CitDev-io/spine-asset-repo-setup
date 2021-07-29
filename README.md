# spine-asset-repo-setup
Convert an art asset folder into a github repo to share output with downstream teammates


## How to Keep This Setup Project Up-to-Date

If you haven't already, clone this repository to your local machine.

If you have it on your local machine, make sure your version of this repo is up-to-date:
```git pull origin main```


## Convert a Local Directory Into a Asset Repo
- Copy all files from the `files` folder in this repository into the ROOT of the art asset folder
- Go to Github.com and create a New Repository under the CitDev-io org, name it something like `art-assets-ludum-dare-47`
- Once the repo is created, open a terminal in the ROOT of the art asset folder and do the following:

```
git init
git add .
git commit -m "setup"
git branch -M main
git remote add origin https://github.com/CitDev-io/art-assets-ludum-dare-47.git
git push -u origin main
```

## That's It!
Now you can visit that repository on Github. See the README for help on managing your new asset repository.
