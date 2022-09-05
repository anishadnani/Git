git init

git add -A

git commit -m "Update"

git remote add origin git@github.com:anishadnani/Docker_Testing.git

git push origin main

###### If errors while pushing
eval "$(ssh-agent -s)"
ssh-add <private-ssh-key-file-name> // eg. id_rsa (not .pub)
###########
