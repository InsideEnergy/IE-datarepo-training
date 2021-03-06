# Your First Commit

![](/images/i-want-to-commit.jpg)

We'll start off by learning how to add a folder to a GitHub repository. This is the basic process you'll go through each time you do a data story - you'll add a new folder to our main `Data-for-stories` repo with all of your data. We'll talk later about what that folder should look like.

For now, we'll practice with my training repo. 

## Why are you making me do this?

**Good question!**

Think of this process as showing your work. In the same way that we always cite where we get photos and graphics, we also want to be as transparent as possible about how we reached the conclusions that data can lead us to.

Various media outlets are doing this to different degrees. Few, however, are doing it in a systematic way, as far as making data available and directing users to it. We'd like to be one of the first to make this a standard process and a routine part of our reporting.

### A bit about how GitHub works

GitHub allows us to clone local directories (folders on our computers) and host them remotely (on the web), so that others can see and do stuff with them. A GitHub repository has a lot of great built-in features that facilitate collaboration on projects as well as easy version control.

Eventually, each of you will clone the remote directory `insideenergy/Data-for-stories` to a local folder on your computer. You'll add things to that local directory on your machine, and push your changes back to the remote.

#### Key thing to keep in mind

When it's time for you to add a new folder full of [awesome data](http://www.tdcj.state.tx.us/death_row/dr_executed_offenders.html), you always want to make sure that the local directory you're working with on your computer is up to date with the remote public directory. This is **super important**, because otherwise you could potentially erase someone else's recent addition by pushing an older version of the directory. 

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

**Check in: has this worked for everyone?**

Okay, saved? Congratulations, you now have the very latest version of this repository. 

#### A note about branches...

In my training repo, and in the `Data-for-stories` repo, we have two branches. That basically means there are two versions of the repo that the public can see. 

The first one, the default, is `master`. It's the final version of the repo, the one that we point the public to when we link to the data from our stories. 

The second one is `staging`. **This is where you'll all be working.** Every time you push a new folder or a change, it will be to the `staging` branch. This is the working branch, the one where, if there are conflicting versions of the repo, or if you need Jordan or I to look at something before it's added to `master`, any issues get resolved.

In order to see which branch you're in, check the top of your GitHub app window. Does it say `staging` or `master`? 

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

In the staging branch, you should see your changes! It will look something like this:

![](/images/new-changes.png)

The GitHub app recognizes that you've changed something in your local directory. Now it's asking you which changes you want to send back to the remote. You have to "commit" to adding the changes to the remote branch. 

Look down at the bottom of the window. In the "Summary" field, type a little description of the changes you want to commit. This helps other who're looking at the remote repo understand what you've done. You can type something like, "added my test folder"

![](/images/commit-message.png)

Now you're ready to commit! (Finally, amirite?)

Click the `Commit to staging` button.

### Step 4

Your changes still aren't on the remote branch yet! We have one more step to go. We've committed the changes we've made, but we still haven't pushed them to the remote. Back at the top of the window, you should see something like this:

![](/images/unsynced.png)

Click on unsynced. You should see your change again. All we have left to do is sync! Look up to the very top right corner of your windown.

![](/images/sync.png)

Click sync.

Congratulations! You've just made your very first GitHub contribution. 

![](http://media.giphy.com/media/PTZjY7PZ03xNm/giphy.gif)

You can go to the [GitHub page online](https://github.com/catharob/IE-datarepo-training/tree/staging), and see your new folder inside the `staging` branch of `IE-datarepo-training`.

### One last thing...

Now you need to let Jordan or I know that you've added a folder, so that we can update the master. To do that, you need to make a pull request. **This happens on the GitHub wepage - the remote (not the local, and not your GitHub app).**

On the page where you can see the staging branch, you should see in the middle somewhere an icon for "pull request":

![](/images/pull-request.png)

Click it. You'll be asked to give a desciption - this can be the same as the one you wrote for the commit. 

Scroll down a little bit, and click the green "Create pull request" button. 

And now, you're done! We'll handle the response to your pull request on our end.