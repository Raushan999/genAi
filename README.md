# Generative AI

#### Commands for pushing files to    `github`

* Installing the packages mentioned in the requirements.txt file.

```
pip install -r requirements.txt
```
* Seeing all the installed packages in the virtual environment.

```
pip list
```
* To know the status of the files
```
git status
```
# If you are not cloning it initialize it locally
``` 
git init 
git remote add origin <repository clone link>
git add .  #--- adding all the files
git commit -m "commit" #--- the message you want to reflext beside the file on github.
git push origin main/master # --- pushing all the files

```
* Make sure your github details `email` and `user-name` are configured properly, otherwise cofig them ussing the error message from the terminal.
# To keep updating the progress.
```
git add .
git commit -m "second commit"
git push -f origin main  # to keep updating the intermediate changes 
```