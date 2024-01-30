# GIS Day 2022

Demonstrates how to use the arcpy module inside an esri ArcGIS Pro software environment.
<br>
To install, just run `gis_day_install.py` or download the project and extract into `C:\Student\GISDay_2022`
<br>
This project was compiled in ArcGIS Pro 2.9.1 so earlier version may give you a warning of incompatibility.  Should work, however. 


## Tips on how to learn Python for GIS Professionals

- Very nicely done [video](https://www.youtube.com/watch?v=-XrfcQVjWcM) that gives a broad overview what Python is and what it can do for GIS professionals. There are plenty of great videos in this YouTube channel. Here's [another one](https://www.youtube.com/watch?v=v1i4odPkv9U) if you want to dig into a more hands on look at python in ArcGIS Pro. 
- [learnpython.org](https://www.learnpython.org/) is a good free option. Not quite as polished as Code Academy, but free and it will hone in on the basic building blocks to get comfortable with the code syntax.
- [codecademy.com](https://www.codecademy.com) has a slick web interface and very effective for learning, but the python 3 tutorial (I don't recommend learning python 2, it is deprecated) will cost you around $17 a month for the Pro Lite version.  I would suggest this if you're serious about learning good Python syntax basics, as you might have an easier time practicing in the web interface. You can also try the free trial for Pro if you're unsure. 
- [freecodecamp.org](https://www.freecodecamp.org/news/freecodecamp-python-courses-ranked-from-best-to-worst/) has a list of Python video tutorials. I've skimmed the first one and it looks very thorough. If you have ArcGIS Pro installed you can skip all the Python installation stuff since it's already installed. 
- Lots of lots of googling. I use keywords all the time like `arcpy delete` or `arcpy list featureclasses` or `arcpy environment variables`. The esri documentation is good and helps you if you get stuck on syntax for arcpy functions.
- Tons of stuff on youtube obviously.
- It's kind of impossible to remember all the syntax for the arcpy functions.  I highly recommend "cheating" and using the graphical tool in ArcGIS Pro and copy the Python command from the "Run" command drop down button.  Study the output, learn from it, modify it, and run it on its own.
- The notebooks built into ArcGIS Pro are a fantastic way to learn. I recommend looking for tutorials online, and [this one from esri](https://learn.arcgis.com/en/projects/get-started-with-notebooks-in-arcgis-pro/) is good to get you acquainted with the interface.  
- Get a good code editor once you want to branch away from Jupyter notebooks inside AcGIS Pro. Besides notebooks, the ones that come pre-installed with ArcGIS are terrible.  I recommend [Sublime Text](https://www.sublimetext.com) but there are [plenty out there](https://www.creativebloq.com/advice/best-code-editors) to choose from. 
- It's good to have a project or goal in mind when venturing out to get better at Python.  What do you want to automate?  Do you have a thousand shapefiles on a network drive that are a [mishmash of projections](https://github.com/rrudolph/arcpy-scripts/blob/master/walk%20and%20separate%20zones%20into%20directories.py) that you need to organize and consolidate?  Do you need to [export all the attachments](https://github.com/rrudolph/gdb-attachment-exporter) from the file geodatabase of a Field Maps project? Do you need to [backup your ArcGIS Online feature services?](https://github.com/rrudolph/pro-tools?tab=readme-ov-file#backup-agol-services-tool) Look for other similar projects or scripts online to help narrow the scope. A smaller project will be less daunting but still provide a valuable learning experience. Keep working on it even if it takes a long time. 
