git remote add origin https://github.com/kartpsg/TestRepo.git
git push -u origin master
git clone https://github.com/kartpsg/TestRepo.git test1/

//working sequence for get from github, change & push back to github.
/...............
git remote add origin https://github.com/kartpsg/TestRepo.git
git pull origin master
//local change & execute
git commit -a
git push origin master
/...............

//Below not yet verified.
git merge orgin/master
//Make changes & commit in local master.
git push origin master
