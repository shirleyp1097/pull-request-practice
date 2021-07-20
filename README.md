# Pull Request Practice Repo

This repository contains instructions for how to practice making pull requests.

## Steps

1. Fork this repository to your GitHub profile
1. Clone the forked version of this repository
1. Create a branch called `first-feature` and checkout to it
   ```
   git checkout -b first-feature 
   ```
1. Add a text file to the root of this project called `first-feature.txt`
   ```
   touch first-feature.txt
   ```
1. Add and commit this change
    ```
    git add .
    git commit -m 'feat: Add first-feature.txt'
    ```
1. Push up the `first-feature` branch
   ```
   git push origin first-feature
   ```
1. Create a pull request for merging `first-feature` into `main`
1. Merge the pull request
1. In your local repository, checkout to your `main` branch
   ```
   git checkout main
   ```
1. Pull the merged changes into your local `main` branch
   ```
   git pull origin main
   ```
1. Create a new branch off of `main` called `second-feature` and checkout to it
1. Add the text `second feature` to the `first-feature.txt` file
1. Add and commit this change
1. Push up the `second-feature` branch, create a PR to main and merge it
1. Checkout to `main` locally and pull from GitHub to update
1. Repeat steps 11-15 several times to get more experience working with pull requests 
