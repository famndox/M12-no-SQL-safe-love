# M12-no-SQL-safe-love

Module 12 Challenge

## Story
So, I was having a terrible time trying to find a business within the 
desired lat/long range in the analysis notebook; tried parsing the 
sections out to troubleshoot and everything. Going back through the 
first notebook I discovered, having copied lines of code from the 
coursework, that I had left in 'Greenwich' from the search&delete
'Dover' section. Therefore, some of the notes may make less sense
and I'll give you a Re-ran prompt below.  
I guess lucky me that I made an error specifically blocking my 
progress that I might notice it. 

## Contents
 * Resources
 * ^^^ establishments.json - before running notebooks; 
 * * convert DB Import Steps to present tense and follow the steps 
 * NoSQL_setup_starter.ipynb - run this notebook first
 * NoSQL_analysis_starter.ipynb - run this notebook last
 
## DB Import Steps
 * Opened Terminal from within the 'Resources' folder (where the .json resides)
 * Ran prompt:   mongoimport -d uk_food -c establishments --jsonArray establishments.json
 * Re-ran prompt: mongoimport --drop -d uk_food -c establishments --jsonArray establishments.json


