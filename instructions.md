Global setup:
 Set up git
  git config --global user.name Your Name
  git config --global user.email MorehouseJ09@gmail.com
      
Next steps:
  mkdir prospero
  cd prospero
  git init
  touch README
  git add README
  git commit -m 'first commit'
  git remote add origin https://github.com/MorehouseJ09/cloudroom_design.git
  git push -u origin master
      
Existing Git Repo?
  cd existing_git_repo
  git remote add origin https://github.com/MorehouseJ09/cloudroom_design.git
  git push -u origin master