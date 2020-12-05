# Final Project

## Script 1
Script one inputs a user-given latitude and longitude to output the weather conditions based on that requested locations. This script uses web scraping, string concatenation, and 
value conversion. By scraping a 5-day weather forecast from the National Weather Service website, this script will take information from multiple elements listed under a same 
class name using a library. Furthermore, this code also uses string editing to modify the objects in the list, adding spaces, capitalizations and substitutions. The process of 
writing this script was not difficult, as the only challenges that were faced during it were standard syntax errors that were fixed with debugging. One of these issues that I ran 
into was trying to figure out how to modify the forecast expressions. We used Stackoverflow.com, which gave a helpful tip about using the re library to aid in finding typos in 
expressions and modifying them. It makes it a lot easier when editing spaces, capitalizations, and standard grammatical errors. Once we imported the re library, the for loop 
editing the strings worked a lot better. 

Because we both plan on working in the GIS field in the future, we plan on using scripts very similar to this in the future. Web-scraping is an extremely important skill, not only 
in international development but also in software development and government development. With climate change and its effects on the uprise, it is becoming increasingly important 
to monitor changes in weather patterns. With this script, the user can input any given location and view its forecast details for the day, which can come in handy for climate 
change scientists and meteorological experts. 


## Script 2
This script analyzes a text document that lists the 708 unique results of a survey determining which county of Kenya is the priority for an humanitarian organization.  Due to cuts 
in funding, the organization produced this survey asking its employees and stakeholders to assess which counties are of highest priority for future projects. Each line of the text 
document indicates: Name – County which means: Name of the survey participant – the county they are voting for

This script contains two code blocks. The first code block creates the first step of editing the data, which was to import the text file from Goolge Drive. The text file was full 
of errors such as repeat votes and odd spacing that created challenges for parsing out the data with Python so the code then addresses the grammatical and syntax errors that make 
counting votes with Python a challenge. The commands .strip, .replace, .lower,  and .split were used to clean up the data inputs so that the data could be measured accurately.  
The code block then counts up the number of votes for an input and calculates the total votes for that particular county.  Code block three works off of the same data source that 
was already imported and creates three functions.  The first function edits and formats the data, counts which voters voted twice and then calculates the total votes for each 
country. 

The errors that we faced in creating this section of code were general syntax errors. Figuring out how to import data from Google drive took the most amount of time to write this 
section of code. After that, the general problems were how to correct spacing so that the code would run and so that our outputs would print the three functions correctly. 

### Resources

This website was used to learn about importing the re library to help modify expressions. https://stackoverflow.com/questions/56200931/regular-expression-matching-in-python

To import the data file from Googe Drive, the following website was used to determine the process and libraries required to give permission to a Google Drive account and access it 
within a code. https://buomsoo-kim.github.io/colab/2018/04/16/Importing-files-from-Google-Drive-in-Google-Colab.md/

This website easily explains how to extract the file Id from Google Drive: https://docs.meiro.io/books/meiro-integrations/page/where-can-i-find-the-file-id-on-google-
drive#:~:text=Google%20Drive%20File%20ID%20is,on%20Link%20Sharing%20if%20needed.
 

