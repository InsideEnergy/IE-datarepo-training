# Your First Commit

![](/images/i-want-to-commit.jpg)

We'll start off by learning how to add a folder to a GitHub repository. This is the basic process you'll go through each time you do a data story - you'll add a new folder to our main Data-for-stories repo with all of your data. We'll talk later about what that folder should look like.

For now, we'll practice with my training repo. 

### A bit about how GitHub works

GitHub allows us to clone local directories (folders on our computers) and host them remotely (on the web), so that others can see and do stuff with them. A GitHub repository has a lot of great built-in features that facilitate collaboration on projects as well as easy version control.

Eventually, each of you will clone the remote directory `insideenergy/Data-for-stories` to a local folder on your computer. You'll add things to that local directory on your machine, and push your changes back to the remote.

#### Key thing to keep in mind

When it's time for you to add a new folder full of [awesome data](http://137.189.35.203/WebUI/CatDatabase/catData.html), you always want to make sure that the local directory you're working with on your computer is up to date with the remote public directory. This is **super important**, because otherwise you could potentially erase someone else's recent addition by pushing an older version of the directory. 

Don't worry too much about that just this second. We'll go over it more later. 

# Let's get started, already.

Okay, okay.

### Step 1

Let's get the remote directory onto your local machine. Go to the training repo's [main page](https://github.com/catharob/IE-datarepo-training).

Look at the right-hand side of the page. You should see a button that says "Clone in Desktop"

![](/images/clone.png)

Click it!

You'll be asked to allow the page to launch your GitHub application, which you all should have installed. Go ahead and launch. 

Next you need to pick a location to save your local directory. It doesn't matter where this is, and you can move it around if you need to. I have a GitHub folder where I keep all my local directories. 

Okay, saved? Congratulations, you now have the very latest version of this repository. 

#### A note about branches...

In my training repo, and in the `Data-for-stories` repo, we have two branches. That basically means there are two versions of the repo that the public can see. 

The first one, the default, is `master`. It's the final version of the repo, the one that we point the public to when we link to the data from our stories. 

The second one is `staging`. **This is where you'll all be working.** Every time you push a new folder or a change, it will be to the `staging branch. This is the working branch, the one where, if there are conflicting versions of the repo, or if you need Jordan or I to look at something before it's added to `master`, any issues get resolved. 

**You'll always be working in the `staging` branch.**

In that spirit, let's make sure we're in the staging branch. At the top of the GitHub app window, you should see something that looks like this:

![](/images/master.png)

Click master, and select staging instead. 

![](/images/staging.png)

From now on, before you make any changes, make sure that you're working in the staging branch. 

Now you can start adding your own data! 

### Step 2

Add a new data folder. Inside your local `IE-datarepo-training` folder, you'll have some files and some folders. Make a new folder here, and name it `my-test-folder-Yourname`.

Now, open up your favorite text editor. Type the following: `# Test Folder Yourname`

Save that file as README.md into the folder you just created, `my-test-folder-Yourname`.

*In the future, you'll use the README to give an explanation of the contents of the folder. You'll also put your CSV and XLS files for your data into this folder.  Again, we'll come back to that. For now, we're just practicing the steps.*

### Step 3

Now, go back to your GitHub app. 