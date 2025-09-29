# test-repo
even # Hello GitHub
git clone https://github.com/YourUserName/test-repo.git
cd test-repo
for i in {1..20}
do
  echo "Update $i" >> log.txt
  git add .
  git commit -m "Commit $i"
done
git push
