## Sub folder with the Clone repo via HTTPS.

So This repo is again created inside the Existing GH repo.

Our motive is to clone a GH repo in local folder in Codespace

Make changes in the readme.md file

Save the file and push the Folder to origin(Main remote GH repo)

## Steps
create a folder in main GH repo
```
mkdir gh-clone-HTTPs
```
```
cd gh-clone-HTTPs
```
Make changes into the existing readme.md file.
```
code readme.md
```
Go back to the main repo
```
cd ..
```
Add the git changes.

```
git add gh-clone-HTTPs
```
Commit the changes.
```
git commit -m "your message"
```
Push to the GH repo.
```
git push
```
## TA daaa
This will be all you need to do.
You have successfuly clone the Existing GH repo.

Make changes and Push to the GH repo.