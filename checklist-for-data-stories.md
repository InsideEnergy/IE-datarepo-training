# Checklist for Every Story

Here is what you should do for **every story you file that includes a data vizualization**. Eventually we also want to do this with any story that uses any data that we've analyzed, even if there isn't a graph. 

### Step 0

This is just a workflow thing, which I recommend so that we minimize the potential for multiple people to push conflicting versions of `Data-for-stories`. As you're gathering all of the following elements to add to our repo, I would create the folder you'll eventually push to GitHub OUTSIDE your local `Data-for-stories` directory. You can add it to your local directory once everything is ready to go. Then, you can make sure you have the very latest verson of `Data-for-stories` before you move in your new folder and push it to GitHub. 

##### Make a folder on your desktop for all of your story's data. 

Use the naming convention for folders inside [`Data-for-stories`](https://github.com/InsideEnergy/Data-for-stories). That is:

`YYYYMMDD-short-description` 

The date should be the **date you published the story to our site**.

Use hyphens for spaces and all lower-case. The description for the folder name should be as short and as clear as possible.

### Step 1

Here are some guidelines for cleaning up your data - but probably the best way to see how it should look on GitHub is just to go to [our page](https://github.com/InsideEnergy/Data-for-stories) and see what I've done.

##### Clean up your data.

The files we make available for download using GitHub should look as clean and simple as possible. The main reason for this is that sometimes when we pull data, like from the BLS, the Excel file contains a lot of extra info that's important, but can make the spreadsheet difficult to use. Like this:

![](/images/bls.png)

All that stuff at the top is important, but makes more sense for us to include in the notes that go with these data files, instead of in the files themselves. So, cleaned up, this should look like:

![](/images/bls-clean.png)

I prefer the column headings to be lower-case and hyphenated, but you can do them however you want. They just need to look clean and consistent. 

##### Once you've cleaned up the data, save into the folder you just created on your desktop.

You should have at least two files of data. Save the cleaned-up dataset once as a `.xlsx` file and once as a `.csv` file. Name them the exact same (except for the extension, obviously). Again, lower case and hyphenated. Usually the best thing is just to use the same short description you used in the name of the folder. (If you have more than one graph for a story, that won't be possible, so just describe the particular data in the file.)

### Step 2

If you don't have a text/code editor you like, I highly recommend [Sublime Text](http://www.sublimetext.com/). This is where you can write your description of the data.

##### Make a README.

In a text editor (like Sublime), open a new blank file and save it to the data folder you've been using on your desktop. 

**You must name it `README.MD`.**

`.md` is the file extension for what's called Markdown, a simple styling language. 

The point of the README is to explain to visitors what this(these) dataset(s) is(are) all about. It should be clear and conversational. The general guiding principle as you write your README is to be as transparent as possible about the analysis that we did with this dataset. 

**You can use a template README that I made.** It's [here](https://raw.githubusercontent.com/catharob/IE-datarepo-training/master/template-README.md). Copy the code directly from that page, or, since you've all cloned `IE-datarepo-training`, you have the template file on your machines wherever you saved that folder. You can open it up, rename it README.md and save into the new folder on your desktop.

If you're interested in playing with the style of your README, I added a [Markdown cheatsheet](https://github.com/catharob/IE-datarepo-training/blob/master/markdown-cheatsheet-online.pdf) that GitHub made. 

### Quick Check

Now, look back. Do you have a .CSV, an .XLSX, and a README.md file in your folder (and extra .CSV and .XLSX files if your story has more than one graph)? Yes?

**Great!**

![](http://media.giphy.com/media/4la2AJWCtl8Pu/giphy.gif)

### Step 3

Now it's time to make sure you have the most recent version of `Data-for-stories`. 

##### Pull the latest repo from the remote. 

It's easy. In your GitHub app, navigate to `Data-for-stories` using the left side of the screen.

![](/images/nav.png)

Now, in the GitHub app's menu bar, click Repository, and select Pull.

![](/images/pull.png)

Now your local Data-for-stories directory should be up to date with the public remote version. To check, go to the [GitHub page](https://github.com/InsideEnergy/Data-for-stories), take a quick look at the list of folders and files, and make sure they match up with what you have on saved on your machine in your local directory. 

Now it's time to push your new folder!

### Step 4

[We've done this before](https://github.com/catharob/IE-datarepo-training/blob/master/your-first-commit.md), so you can refresh yourself on the process if you need to.

##### Get in the right branch!

In your GitHub app, make sure you're working in the `staging` branch and NOT the `master`. (You can change branches at the top of the window.)

##### Add your new folder to your local directory.

Drag your new folder (the one that contains your cleaned data files and README) into your local `Data-for-stories` directory. Now, in you GitHub app, you should be able to see the folder listed under "changes".

### Step 4.5

One other quick change we need to make: We need to update the README for the larger `Data-for-stories` folder. In your local directory, open up the README.md in a text editor.

![](/images/readme-location.png)

You'll see the Markdown format for a table - this is the table that lists all of the data folders in the repo and the stories they're connected with. 

Add your story - the date, the title of the story that links out to our website, and the name of the folder that contains your data (the one that starts with the date). You can copy the formatting for all the other entries. 

**Hit save.** Now that change should also show up in your GitHub app. 

##### Commit!

Add a comment in the "Summary" field on your GitHub app for the changes you've made. Click "Commit to staging". 

##### Push!

At the top of the window, click over to "Unsynced". You should see the same changes you just committed. 

Click "Sync" in the top right corner of the window. 

##### Check yourself.

Go to the GitHub page for `Data-for-stories`. Do you see your new folder in the `staging` branch? Yes? **Awesome.**

### Step 5

Now you need to let Jordan/me know that your changes are there, so that we can merge them with the `master` branch. [We've done this before](https://github.com/catharob/IE-datarepo-training/blob/master/your-first-commit.md) as well. 

##### Pull request.

On our GitHub page, click into the folder you just added in the `staging` branch. Above the list of files, you should see a button for "Pull request". Click it, add a comment (same as your commit comment, is best), then click green "Create pull request" button.

![](/images/pr-comment.png)

##### Merge, if possible. 

Now, it might be the case that your changes don't conflict with anything anyone else has done (likely, if you remembered to pull the most recent version of the remote repo). If that's the case, then after you pull request, you might see this:

![](/images/merge.png)

That's great! GitHub is actually pretty smart about seeing exactly which lines of new code or text conflict with each other. If it doesn't find anything weird, it will let you merge without going though me or Jordan. That makes everything great for all of us. 

So if you see the option above, by all means, click it!

Now your changes should be in both the `staging` and `master` branches.

### Step 6

Seriously? There's more?

##### Just a little bit. You can do it!

![](http://media.giphy.com/media/tvWi7KBvkTLP2/giphy.gif)

##### Now we need to add the data to Google Sheets. 

Make a new sheet inside [this folder](https://drive.google.com/drive/u/1/folders/0B82exFJJWyJqfkxtTERNT2NjQ1BOa0RuZVBGWjA3RC1zWVNTV3NxWnNrQW5MbGgtdjZibVk).

Copy and paste the data from the CSV or Execl file into the sheet. 

**Note:** If you have time-series data that's listed by month and year, be careful that those fields copy over in the right format. You may have to reformat those cells to be the right month and year combo. 

Name the sheet with the date you published the story and the same short description you used for the folder you added to `Data-for-stories`. 

Now, change the sharing settings so that anyone on the web can see but not edit the spreadsheet.

![](/images/sheets.png)

### Step 7

All that's left is to link to the files we just made in the story on our website!

##### Make download links for the CSV and XLSX files.

We have to make a URL for the CSV and XLSX files we just added to GitHub that will allow a direct download of the data, with the click of a link. The general form of that URL is:

`http://rawgit.com/insideenergy/Data-for-stories/master/FOLDER/FILENAME.csv`

`http://rawgit.com/insideenergy/Data-for-stories/master/FOLDER/FILENAME.xlsx`

The capital letter fields are what you should replace. Add the name of the folder you just made and the name of the file for the CSV and the XLSX files you just made. 

Those URLs, the view-without-editing sharing link for the Google sheet, and the link for the GitHub folder you just made, should be pasted into this code:

`<small><strong> Get the data: <a href="CSV URL YOU JUST MADE">CSV</a> | <a href="XLSX URL YOU JUST MADE">XLS</a> | <a href="GOOGLE SHEETS LINK YOU JUST MADE">Google Sheets</a> | Source and notes: <a href="URL FOR YOUR FOLDER ON GITHUB">Github</a> </strong></small>`

Then, that code should go directly under the graph that uses this data. 

### Step 8

Update the story and check to make sure the links are working. 

# You're done!!!!
