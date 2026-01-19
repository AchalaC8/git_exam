# git_exam
<p>This repository is made to demonstrate one of the git advanced operation that is cherry-pick
</p>

# COMMANDS USED
<p>
  git config --global user.name
  git config --global user.email 
  git clone 
  cd
  echo "" >file_name.py
  git add .
  git commit -m "commit message"
  git remote -v
  git push -u origin main
  git branch
  git checkout 
  git log --oneline
  git cherry-pick <Oldest_commitID>^..<Newest_commitID>
</p>

# Command execution sequence 
<p>
  git config --global user.name "AchalaC8"
  git config --global user.email "chandruachala9@gmail.com"
  git clone "https://github.com/AchalaC8/git_exam.git"
  cd git_exam
  echo "print("this is main program")" >main.py
  git add .
  git commit -m "This is main program"
  git remote -v
  git push -u origin main
  git branch source-branch
  git checkout source-branch
  echo "print("this is feature 1")" >file1.py&&git add .&&git commit -m "feature 1 commited"
  echo "print("this is feature 2")" >file2.py&&git add .&&git commit -m "feature 2 commited"
  echo "print("this is feature 3")" >file3.py&&git add .&&git commit -m "feature 3 commited"
  echo "print("this is feature 4")" >file4.py&&git add .&&git commit -m "feature 4 commited"
  echo "print("this is feature 5")" >file5.py&&git add .&&git commit -m "feature 5 commited"
  git push origin source-branch
  git log --oneline
  git checkout main
  git cherry-pick a5e099f^..2f05ba1
  git push
  
</p>

