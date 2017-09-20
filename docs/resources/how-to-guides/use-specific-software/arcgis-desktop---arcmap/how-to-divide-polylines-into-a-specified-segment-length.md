---
title: How to divide polylines into a specified segment length
---



### Case study: Escalante Watershed NHD perennial streams divided into 100 m segments

Prepared by Wally Macfarlane, 10/5/2012 

This tutorial is for ArcGIS 10 Service Pack 4. 

Step 1: Merge all segments together (otherwise you’ll need to run this command for each segment). 

Use the merge command under Editor. 

Step 2: Download the [Editing Labs Divide Line By Length Add-in](http://www.arcgis.com/home/item.html?id=d5d27ee47330434b9a96b91136a0118f)

**Installation and use:**

1. Download and double-click the file.
2. To use the add-in, you must first add it to a toolbar in ArcMap. Click the Customize menu and click Customize Mode. Click the Commands tab and type Divide Line in the search box. Drag the Divide Line By Length command from the Editing Labs category onto any toolbar, such as the Editor or Advanced Editing toolbar.
3. Click the Edit tool on the Editor toolbar and select the line that you would like to split. 
4. Click Divide Line By Length on the toolbar to which you added it. 
5. Type the length value you want to use to divide the line.
6. Press ENTER to split the line. If the length entered does not divide evenly into the line’s length, the remaining leftover distance is not allocated among the new features.

Note: Make sure your Add-In Manger settings are as follows:

![screenshot]({{ site.baseurl }}/assets/images/screenshot.png)

For this exercise I simply selected the line segement (which in this case was the entire Escalante drainage network) click on the tool and then in the pop-up box typed 100. Because my projection is in meters it the command divides by 100m segments. This may take a few minutes if you have a large drainage network.