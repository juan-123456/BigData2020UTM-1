# BigData2020UTM

+ Big Data: is the storage or data set whose volume, speed, processing are much larger than a database.
***

+ The importance of the data: Your data is important because if someone gets your data. You can impersonate your identity or even get your bank account and grab the money. Now that your data is already becoming digital, they have become much more important.
***

+ Difference between private and open data: Virtually open data is easily found while private data is not.
***

+ Difference between structured and unstructured data: Structured data is data that is easy to search while unstructured data is difficult to search as well as multimedia files.
***

+ Difference between stored and moving data: The stored data are structured and generate information and the moving data are the ones that are circulating in the network.
***

+ Data analysis: It is responsible for examining the data in order to draw a conclusion about the information.
***

+ Impact of data analytics: the impact it has is that companies can now earn income through data analysis
***

+ Different types of data analytics
-Descriptive: In a business it allows you to see the main metrics within the business. For example, gains and losses in the month, sales made, etc.
-Diagnostic: You must have the necessary tools so that the analyst can deepen the data and isolate the root cause of a problem.
-Predictive: Predictive analysis has to do with prediction. Either the probability of an event occurring in the future, the forecast of a quantifiable amount or the estimation of a point in time at which something could happen - all of them are done through predictive models.
-Prescriptive: The prescriptive model uses an understanding of what has happened, why it has happened and a variety of "what could happen" analysis to help the user determine the best course of action to take. The prescriptive analysis is usually not only with an individual action, but in fact it is a series of other actions.
***


+ Docker: The idea behind Docker is to create lightweight and portable containers for software applications that can be used on any machine with Docker installed, thus also facilitating the deployment or execution of the software.
***

+ MapReduce: it is a framework that provides a parallel and distributed data processing system and is aimed at solving problems with large data sets, so it uses the HDFS distributed file system.
***

+ Hoodoop: is a set of open source programs and procedures that anyone can use as the “backbone” of their Big Data operations.
***

+ Apache Spark: The idea is that we have n machines, for example ten machines, and each of those instances will have a version of Apache Spark installed. In this way, when we have to process a large amount of data, for example a very large file, we can divide it into ten parts, and each machine will handle a tenth of the file, and in the end we will join it.
***

+ Lamba and Kappa: Its objective was to have a robust fault-tolerant system, both human and hardware, that was linearly scalable and that allowed writing and reading with low latency, while kappa points to "weak" Lambda Architecture and how to solve them through an evolution Your proposal is to eliminate the batch layer leaving only the streaming layer.
***

> Commands

+ Git init: Create a new repertoire
```javascript
Usuario@AERO MINGW64 ~/Desktop/Prueba (master)
$ git init
Reinitialized existing Git repository in C:/Users/Usuario/Desktop/Prueba/.git/
}
```
***
+ Git status: Shows the list of the files, along with the files that are about to be added
```javascript
Usuario@AERO MINGW64 ~/Desktop/Prueba (master)
$ nano bigdata.txt

Usuario@AERO MINGW64 ~/Desktop/Prueba (master)
$ git status
On branch master
Your branch is up to date with 'origin/master'.

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        bigdata.txt

nothing added to commit but untracked files present (use "git add" to track)
}
```
***

+ Git add: This command can be used to add files
```javascript
Usuario@AERO MINGW64 ~/Desktop/Prueba (master)
$ git add bigdata.txt
warning: LF will be replaced by CRLF in bigdata.txt.
The file will have its original line endings in your working directory
}

```
***

+ Git commit: Used to change the header
```javascript
Usuario@AERO MINGW64 ~/Desktop (master)
$ git commit --amend
[master 2bbd870] Prueba123
 Date: Fri Jan 31 13:03:20 2020 -0600
 1 file changed, 1 insertion(+)
 create mode 100644 index.html
}
```
***
+ Git reset: Remove commits.
```javascript
Usuario@AERO MINGW64 ~/Desktop/Prueba (master)
$ git reset index.html
Unstaged changes after reset:
M       index.html

Usuario@AERO MINGW64 ~/Desktop/Hola (master)
$ git status
On branch master
Your branch is ahead of 'origin/master' by 2 commits.
  (use "git push" to publish your local commits)

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   index.html

no changes added to commit (use "git add" and/or "git commit -a")

}
```
***

+ Git log: Shows a list of commits in a branch along with all the details
```javascript
Usuario@AERO MINGW64 ~/Desktop/Prueba (master)
$ git log
commit b77348c433f7a5fae9e5cdd591e22870544f4549 (HEAD -> master)
Author: Andres Ramirez <aero.1715@hotmail.com>
Date:   Fri Jan 30 21:39:05 2020 -0600

    First project

}
```
***
+ Git rm: It is used to remove files from the index and the directory you are working on
```javascript
Usuario@AERO MINGW64 ~/Desktop/Prueba (master)
$ git rm bigdata.txt
rm 'bigdata.txt'
Usuario@AERO MINGW64 ~/Desktop/Prueba (master)
$ git status
On branch master
Your branch is ahead of 'origin/master' by 1 commit.
  (use "git push" to publish your local commits)

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        deleted:    bigdata.txt

}
```
***
+ Git mv: Used to move a file
```javascript
Usuario@AERO MINGW64 ~/Desktop/Prueba (master)
$ git mv Pagina1.html index.html

Usuario@AERO MINGW64 ~/Desktop/Prueba (master)
$ git status
On branch master
Your branch is ahead of 'origin/master' by 1 commit.
  (use "git push" to publish your local commits)

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        deleted:    bigdata.txt
        renamed:    Pagina1.html -> index.html
}
```
***
+ Git commit --amend: We can modify the most recent confirmation and even combine changes.
```javascript
Usuario@AERO MINGW64 ~/Desktop (master)
$ git commit --amend
[master 2bbd870] Prueba123
 Date: Fri Jan 31 13:03:20 2020 -0600
 1 file changed, 1 insertion(+)
 create mode 100644 index.html
}
```

:closed_book:
