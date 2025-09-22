mkdir as1 
cd as1
git init
touch file1.txt
git status
git add file1.txt
git commit -m "First added file (file1.txt)"
git branch new-branch
git checkout new-branch
touch file2.txt
git add file2.txt
git commit -m "Second file added (file2.txt)"
git checkout master
git merge new-branch