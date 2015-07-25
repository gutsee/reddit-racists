# reddit-racists
A list of RES tagged racists for your Racism Emphasis Suite pleasure.

This list is curated. Functionally that means that I do a cursory check of every name on the list (this is a horrible job that no one should have to do). I'd also like to have some kind of approved contributors, but we'll see what happens.

Currently the list is being auto-scraped from the top(24 hour) posts in known racist subreddits. There's no quality control to this other than the fact that these users have made top posts, which frankly should be enough.

If you want to add to this list or remove from this list, fork the repo and issue a pull request, or simply send me a message on Github.

<h2>How To Use This List</h2>

Don't do this if you value your existing tags. It will completely replace them, unless you know how to properly concatenate the old and the new. A utility to do this will follow.

Go to any Reddit page with RES active.

Press <code>.</code> to pull up the RES console. Enter <code>RESStorage update RESmodules.userTagger.tags</code>.

A window will pop up, with a text area that houses your existing RES tags. MAKE A BACKUP OF YOUR TAGS BEFORE DOING ANYTHING. 

Find the <code>racists.json</code> file in this repository. You'll probably want to select the "Raw" option here on Github and then do Ctrl+A to select all.

Copy and paste the contents of racists.json (from this repository) into the RES tag box. Hit <code>Confirm</code> to save.

Currently this flags racists as "Racist" in red. I plan to make the tag configurable in the future.
