To initialize a new repo in a new folder, follow these steps:

1. Open a terminal window and navigate to the directory where you want to create your new repo.
2. Run the following command:

```
git init
```

This will create a new `.git` directory in the current directory. This directory contains all of the information that Git needs to track changes to your project.
3. Once you have initialized your repo, you can start adding files to it. To do this, run the following command:

```
git add <filename>
```

You can also add all of the files in the current directory to the repo by running the following command:

```
git add .
```

4. Once you have added all of the files that you want to track, you can commit them to the repo by running the following command:

```
git commit -m "Commit message"
```

The commit message should be a brief description of the changes that you made.

5. Once you have committed your changes, you can push them to a remote repository, such as GitHub. To do this, run the following command:

```
git push origin master
```

This will push your changes to the `master` branch of the remote repository.

Here is an example of how to initialize a new repo in a new folder:

```
# Create a new directory for your repo
mkdir my-repo

# Navigate to the new directory
cd my-repo

# Initialize the repo
git init

# Create a new file
touch README.md

# Add the file to the repo
git add README.md

# Commit the file to the repo
git commit -m "Initial commit"

# Push the changes to a remote repository
git push origin master
```

Once you have pushed your changes to a remote repository, you can start working on your project and collaborating with others.
