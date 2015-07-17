# Troubleshooting

Whenever you (the reporters) have questions, I'll work with you to figure them out, and then I'll post the question and answer here, so that everyone else can see, in case they have the same question. 

## Questions List

Date | Question
---- | --------
July 17. 2015 | What if I forget to switch to the `staging` branch, and my changes show up in `master` instead?

#### What if I forget to switch to the `staging` branch, and my changes show up in `master` instead?

No problem. Easy fix. Don't stage anything to commit - go to your GitHub app. In the `master` branch where your changes are, look at the list and make sure the changes are all checked as selected. Right click on one of the changes listed.

![](/images/troubleshooting-branches.png)

Select "Discard Changes". Do this for each change listed - but remember what they were!

**Now that `master` is empty of changes, switch back to `staging`.**

Now go back to your files. Change something else in each one - just something simple like adding a space or capitalizing something. Now resave each one. 

Check your GitHub app again. Your new changes should show up in `staging` now, instead of `master`!


