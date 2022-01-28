---
title: Keeping all your measures in one place
description: Keeping all of the measures that you create, in one place, helps
  you, and your users find them easier.
author: Marc
date: 2022-01-24T10:41:21.694Z
tags:
  - post
  - featured
image: /assets/blog/bad_sales.png
imageAlt: how do your measures live like this!?
---
So, you have created your last measure, every possible scenario has been thought about. You have created 35 measures and you are at peace with your report. You give it to your recipient who then asks you to add in a new page containing some of the measures you have created.
Wait, where did you put YTD Sales again? What about Same Period Last Year Units?!
ARGH!! where are they.
After 25 minutes of poking around you have finally found your measures and added the page.

What if you could save future you this headache?

Well, measure folders are your answer. Below I will illustrate just how convenient they are. Once you have set them up, you will do the same for every report you create going forwards.

So we start out having all our measures living wherever we created them in the first instance:

![This is bad!](/assets/blog/bad_sales.png "This is bad")

We want to end up with our measures looking like this:

![Ahh much better](/assets/blog/best_sales.png "Much Better")

See how much easier that would be to work with?

Ok, first we need to create a folder for our measures to live in

* Hit the Enter Data dropdown
* Select "Blank Query"

  ![Measure Table Code](/assets/blog/addmeasures_table.png "Measure Table Code")

  [code](/assets/code/MeasuresTable.m)
* The above code will give you a blank table, rename this blank table to something sensible that you will recognise.

  * NOTE: "Measures" is a keyword within PowerBI and cannot be used

You now have somewhere for your measures to live.

Our next step will be to move all of our measures into this folder.

You can do this by entering the model tab:

![Model Tab](/assets/blog/model_tab.png "Model Tab")

In here you can select the table that your measures currently reside in and they will be listed on the right.

Select the measures you want to move:

![Selected Measures](/assets/blog/highlight_measures.png "Selected Measures")

In the Properties pane, you can change the Home Table to your newly created Measures Table:

![Change Home Table](/assets/blog/changemeasures_table.png "Change Home Table")

Now repeat this for each measure that you want to move, if you are moving some measures, I recommend moving them all so that they are all in one easily accessed place.

So now we're in a good position:

![We're almost there](/assets/blog/better_sales.png "We're almost there")

Now, if you've only got three measures as pictured above, then you can stop here.

If, however, you have a whole bunch of measures that would benefit from being categorised. We can go one step further and put them into sub folders, like this:

![Sub folders are great](/assets/blog/best_sales.png "Sub folders are great")

Select the measures you want to group together.

In the Properties pane, change the Display Folder to a value that means something to you:

![Add Sales Sub Folder](/assets/blog/addmeasures_subtable.png "Add Sales Sub Folder")

You can see that it automatically creates the folder, underneath your measures table, and places the measures within it. 

Do this for each category of measures that you want to categorise, you can even have sub-sub folders. If you wanted to do this, instead of just entering Sales in the display folder, you would enter something like Sales\Time Intelligence (must be \ not /)

And there you have it.

All of your measures are now in one place and categorised, making for a much nicer development experience.