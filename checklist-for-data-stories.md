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

Great! 

![](http://media.giphy.com/media/4la2AJWCtl8Pu/giphy.gif)



