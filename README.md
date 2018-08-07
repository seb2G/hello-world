# hello-world

https://guides.github.com/activities/hello-world/
1. By default your repository has one branch named master
2. When you create a branch off the master branch, you’re making a copy, or snapshot, of master as it was at that point in time.
3. Open a Pull Request > Merge your Pull Request > Delete Branch (since the change is already merged there is no need for tha branch anymore) 


https://www.tutorialspoint.com/git/git_basic_concepts.htm
1. DVCS //Distributed Version Control System 
2. DVCS clients not only check out the latest snapshot of the directory but they also fully mirror the repository. If the server goes down, then the repository from any client can be copied back to the server to restore it. Every checkout is a full backup of the repository. Git does not rely on the central server and that is why you can perform many operations when you are offline. You can commit changes, create branches, view logs, and perform other operations when you are offline. You require network connection only to publish your changes (push changes) and take the latest changes (pull changes).
Though Git mirrors entire repository, the size of the data on the client side is small. This illustrates the efficiency of Git at compressing and storing data on the client side.
3. Security - Git uses a secure hash function (SHA1) to name and identify objects within its database. Every file and commit is checksummed and retrieved by its checksum at the time of checkout.
