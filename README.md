# REPORT FOR THE GIT PROJECT.

## Setting up git.

### Installation.
To install git open the terminal and run the following command;

```bash
sudo apt install git-all
```
Though this is the command for installing git on my local machine, git was already installed.


### Configuration.

Configure your email address and username on git.

![alt text](<Screenshot from 2024-07-02 10-21-50-1.png>)

## Git commits to commit.
Create a subdirectory named hello in work directory and inside it a file titled hello.sh with the following content 'echo "Hello, World"' .

```bash
mkdir hello
cd hello
echo 'echo "Hello, World"' > hello.sh
cat hello.sh
```

The output will be as follows:
```bash
echo "Hello, World"
```



Initialize git repository in the hello directory.

![alt text](<Screenshot from 2024-07-02 10-47-35.png>)


Check git status.

![alt text](<Screenshot from 2024-07-02 10-48-17.png>)

### Change the contents of hello.sh.


### Modify hello.sh content.
First commit is to add a comment to line three. Used nano text editor for this part.
![alt text](<Screenshot from 2024-07-02 11-27-52.png>)
![alt text](<Screenshot from 2024-07-02 11-25-16.png>)

For the second commit which changes the content of line 4 and 5, I used nano to make the changes
![alt text](<Screenshot from 2024-07-02 11-28-16.png>)
![alt text](<Screenshot from 2024-07-02 11-26-08.png>)

## History.
### Show history of working directory.
![alt text](<Screenshot from 2024-07-02 11-37-12.png>)

### Show one-line history with only commit hashes and messages.

![alt text](<Screenshot from 2024-07-02 11-37-56.png>)


### Controlled entries

![alt text](<Screenshot from 2024-07-02 11-40-50.png>)

Since I had performed my commits a bit earlier than five minutes you can see the output was blank. But I have used the time variable of one hour so that you can have a better view of the output.

### Personalized format.
Show logs in a personalized format including commit hash, date, message, branch information and author name: * e4e3645 2023-06-10 | Added a comment (HEAD -> main) [John Doe].

![alt text](<Screenshot from 2024-07-02 11-43-41.png>)

## Check it out.
### Restore First Snapshot.
![alt text](<Screenshot from 2024-07-02 12-01-04.png>)

### Resort Second. Recent Snapshot.
![alt text](<Screenshot from 2024-07-02 12-02-46.png>)

### Returning to Latest Version.
![alt text](<Screenshot from 2024-07-02 12-05-43.png>)

## TAG me.
### Referencing Current Version.

![alt text](<Screenshot from 2024-07-02 12-16-30.png>)

### Tagging Previous Version.

![alt text](<Screenshot from 2024-07-02 12-22-19.png>)

### Navigating Tagged Versions.

![alt text](<Screenshot from 2024-07-02 12-24-39.png>)

## Changed your mind?
### Reverting Changes.

![alt text](<Screenshot from 2024-07-02 14-10-00.png>)


### Staging and Cleaning.

![alt text](<Screenshot from 2024-07-02 14-15-15.png>)

### Commiting and Reverting.

![alt text](<Screenshot from 2024-07-02 14-29-01.png>)
![alt text](<Screenshot from 2024-07-02 14-29-40.png>)

 ### Tagging and Removing Commits.
 
 ![alt text](<Screenshot from 2024-07-02 14-34-34.png>)

### Displaying Logs with Deleted Commits.

![alt text](<Screenshot from 2024-07-02 14-56-52.png>)

### Cleaning Unreferenced Commits

![alt text](<Screenshot from 2024-07-02 14-40-46.png>)

### Author Information

![alt text](<Screenshot from 2024-07-02 15-15-01.png>)
![alt text](<Screenshot from 2024-07-02 14-58-18.png>)

![alt text](<Screenshot from 2024-07-02 15-07-31.png>)
![alt text](<Screenshot from 2024-07-02 15-07-48.png>)


## Move it
```bash
mkdir lib
git mv hello.sh lib/
touch Makefile
```



## Blobs, trees and commits
### Exploring .git/ Directory

![alt text](<Screenshot from 2024-07-16 09-52-21.png>)


### Latest Object Hash

![alt text](image.png)