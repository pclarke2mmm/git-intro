## Making Changes With Git

After you have [cloned the repo](README.md), you can start making changes to the code in the repository. Follow the steps below to make changes.

### Creating a Branch

Run the following command to create a branch.:

```bash
git checkout -b yourBranchName
```

### Create or update files

Next, create or update some files.

Then use these commands to add and commit your files:

```bash
git add filename1
git add filename2
git commit -m "I created/modified filename(s)!"
```

Run these commands to try it all in one line:

bash

```bash
for d in {1..6}; do touch file$d.md; git add file$d.md; git commit -m "adding file $d"; done
```

powershell

```powershell
for ($d=1; $d -le 6;$d++) { touch file$d.md; git add file$d.md; git commit -m "adding file$d.md";}
```

Next Step: [Creating a Pull Request](CreatingAPullRequest.md)

[Back To Repo Home](../)
