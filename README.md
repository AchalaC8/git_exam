# git_exam
<p>This repository is made to demonstrate one of the git advanced operation that is cherry-pick
</p>

# COMMANDS USED
<p>
  git config --global user.name</p>
  <p>git config --global user.email </p>
  <p>git clone </p>
  <p>cd</p>
  <p>echo "" >file_name.py</p>
  <p>git add .</p>
  <p>git commit -m "commit message"</p>
  <p>git remote -v</p>
  <p>git push -u origin main</p>
  <p>git branch</p>
  <p>git checkout </p>
  <p>git log --oneline</p>
  <p>git cherry-pick <Oldest_commitID>^..<Newest_commitID>
</p>

# Command execution sequence 
<p>
  git config --global user.name "AchalaC8"</p>
  <p>git config --global user.email "chandruachala9@gmail.com"</p>
  <p>git clone "https://github.com/AchalaC8/git_exam.git"</p>
  <p>cd git_exam</p>
  <p>echo "print("this is main program")" >main.py</p>
  <p>git add .</p>
  <p>git commit -m "This is main program"</p>
  <p>git remote -v</p>
  <p>git push -u origin main</p>
  <p>git branch source-branch</p>
  <p>git checkout source-branch</p>
  <p>echo "print("this is feature 1")" >file1.py&&git add .&&git commit -m "feature 1 commited"</p>
  <p>echo "print("this is feature 2")" >file2.py&&git add .&&git commit -m "feature 2 commited"</p>
  <p>echo "print("this is feature 3")" >file3.py&&git add .&&git commit -m "feature 3 commited"</p>
  <p>echo "print("this is feature 4")" >file4.py&&git add .&&git commit -m "feature 4 commited"</p>
  <p>echo "print("this is feature 5")" >file5.py&&git add .&&git commit -m "feature 5 commited"</p>
  <p>git push origin source-branch
  <p>git log --oneline</p>
  <p>git checkout main</p>
  <p>git cherry-pick a5e099f^..2f05ba1</p>
 <p> git push
  
</p>

