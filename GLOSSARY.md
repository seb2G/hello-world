BLOB - Binary Large Object; each version of a file is represented by blob. A blob holds the file data but doesn’t contain any metadata about the file. It is a binary file, and in Git database, it is named as SHA1 hash of that file.

Branch - Used to create another line of development. Usually, a branch is created to work on a new feature. Once the feature is completed, it is merged back with the master branch and we delete the branch.

Clone - Creates an instance of the repository. Clone operation not only checks out the working copy, but it also mirrors the complete repository. 

Commit - A commit is named by SHA1 hash. You can consider a commit object as a node of the linked list. Every commit object has a pointer to the parent commit object. From a given commit, you can traverse back by looking at the parent pointer to view the history of the commit. If a commit has multiple parent commits, then that particular commit has been created by merging two branches.

Git - Revision Control System, tool to manage your system

GitHub - Hosting service for Git repositories

HEAD - A pointer to the latest commit. Whenever you make a commit, HEAD is updated with the latest commit. The heads of the branches are stored in .git/refs/heads/ directory.

Revision - Represents the version of the source code. Revisions in Git are represented by commits. These commits are identified by SHA1 secure hashes.

Staging Area (Index) - Whenever you do commit, Git will look for the files present in the staging area. Only those files present in the staging area are considered for commit and not all the modified files. You add to the staging area by executing add operation 

Tag - A meaningful name for a specific revision in the repository

Tree - An object that represents a directory. It holds blobs as well as other sub-directories. A tree is a binary file that stores references to blobs and trees which are also named as SHA1 hash of the tree object.

URL - Represents the location of the Git Repository
