What Is Version Control System(VCS)?
Version control is a system that records changes to a file or set of files over
time so that you can recall specific versions later.
We can find 3 Types of VCS's
▪ Local Version Control System
▪ Centralized Version Control System
▪ Decentralized Version Control System


What Is Version Control System(VCS)?
Local Version Control System
▪ It has a simple database that keeps all
changes to files under revision control.
▪ Installed and Maintained usually on a single main system.
▪ One of the most popular VCS tools was a
system called RCS, which is still distributed with many computers today.


Centralized Version Control Systems
These systems (such as CVS, Subversion, and Perforce) have a single server that contains all the
versioned files, and a number of clients that check out files from that central place. For many years,
this has been the standard for version control.


Advantages:
▪ Everyone knows to a certain degree what
everyone else on the project is doing.
▪ Administrators have fine-grained
control.


Drawbacks:
▪ If the single server goes down Or gets
problems, the entire team will get struck
and no further development will be
taken place until unless the server gets
repaired or maintained.


echo "# LearnGit" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/Sadhasivams/LearnGit.git
git push -u origin main
…or push an existing repository from the command line
git remote add origin https://github.com/Sadhasivams/LearnGit.git
git branch -M main
git push -u origin main
