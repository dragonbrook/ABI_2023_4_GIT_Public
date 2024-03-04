git clone https://nametherepository.git
# Execute this command from the directory that is supposed to become the working directory. Copy name and path of the repository from github, e.g.:
# git clone https://github.com/dragonbrook/ABI_2023_4_GIT_Public.git

git add filename.extension
# this adds the file to the staging area

git status
# this shows whether there are new files in the working directory and which files have been added to staging

git commit -m "Comment that should be added to the commit so I will now whatever the F is the point of the commit"
# commits files from the staging area into the LOCAL repository

git push
# Pushes the content of the local repository to the online repository
