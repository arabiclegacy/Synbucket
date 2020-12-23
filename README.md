Copyright (C) 2020 - ArabicLegacy - www.arabiclegacy.github.io
Synbucket executable file is free: you can redistribute it and/or  
modify it under the terms of the GNU General Public License 
as published by the Free Software Foundation, either 
version 3 of the License, or any later version.
Synbucket is distributed 'as-is' in the hope that it will be 
useful, but WITHOUT ANY WARRANTY; without even the implied
warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR 
PURPOSE. See the GNU General Public License for more details.


#Synbucket
----------
Synbucket is a tool to add and rehearse synonyms. It can be used effectively for learning languages vocabularies. Its idea is to provide a way for quickly revising some synonyms that user adds himself to his words database.
Therefore, it has basically two main functionalities: Adding Synonyms or Revising Synonyms. 

When user adds synonyms, it will be added to one associated CSV file called `Bucket.csv`. When user revises synonyms, Synbucket will load words that have been saved in user database.
Using Synbucket, user can be able to rehearse about 50 words in about 10 minutes (if he can recall it in enough time). When user gets familiar and certain about what he memorized in Bucket.csv, he can archive these words 
into another database called `Depot.csv`. User has the option to rehearse words from either `Bucket.csv` or `Depot.csv`. But when he adds new words, it will be added to `Bucket.csv` directly. To move words from `Bucket.csv` 
into `Depot.csv`, user has to click on 'archive' option.

WITHOUT `Bucket.csv` AND `Depot.csv` SYNBUCKET WILL NOT RUN, THESE TWO FILES ARE MUST TO EXIST WITH THE SAME DIRECTORY OF SYNBUCKET.

To have a review over what is saved in user database, there is one feature to review either `Bucket.csv` or `Depot.csv`. There, the user can delete some words, order them, shuffle them.

# How to use Synbucket
----------------------
Synbucket can run in two modes: either in Graphical User Interface (GUI) mode or Command Line Interface (CLI) mode. In GUI mode you will have leverage way for adding new words or revising stored words ad reviewing your database as well.
Default execution assumes GUI mode is running.

## Running in Windows:
Synbucket can be invoked by running the executable file Synbucket.exe or from command terminal by simply typing:
```
Synbucket.exe
```
If you need to rehearse or add words using CLI mode simply in a command terminal type:
```
Synbucket.exe CLI
```

## Running in Linux:
Same as before, for running in GUI:
```
Synbucket
```
For running in CLI: 
```
Synbucket CLI
```


#Specifications
## Addition
- User can add word or phrase with its synonym so that he can insert this synonym pair to an associated CSV file.
- By clicking on "Add Synonym", synonym pair provided in "Word" and "Meaning" fields; will be added into Bucket.CSV.
- There are two CSV files: Depot.csv and Bucket.csv.
- Bucket.csv: is the CSV file that accepts new inputs from the user. This means recent synonyms will be stored in this CSV file only.
- Depot.CSV: is the CSV file that will store old or archieved synonyms.
- User can clear "Word" and "Meaning" fields by clicking on "Clear Fields".
- User can push recent synonyms from Bucket.csv into Depot.csv using "Archive New Words" button. This will empty the Bucket.csv.

## Revision
- To start the revision, user has to choose "Revise Words" tab and hit Enter key to start the revision process.
- User has to answer the interactive questions in order to go further in the revision cycle.
- Upon finishing all revision questions, user can review his answers by clicking on "Show Detailed Results".
- A score will be displayed also to know how many words were correctly answered.
- User can repeat another revision cycle by clicking on "Reset Revision" button.

## Review
- In "Review List" tab, User can review content of `Depot.csv` by clicking on "Review Archived Words" or  he can review content of `Bucket.csv` by clicking on "Review Recent Words".
- In any of the displayed database (Archived or Recent), user can choose to delete certain row by typing the row index and clicking on "Delete Row" button.
- User can order the content of `Bucket.csv` or `Depot.csv` aplhabitcally  by clicking on "Order Alphabitcally" button.
- User can shuffle order the content of `Bucket.csv` or `Depot.csv` by clicking on "Shuffle" button.
