# ChicagoCrime2018

<https://data.cityofchicago.org/Public-Safety/Crimes-2001-to-present/ijzp-q8t2> <br>

The city of Chicago provides crime records to the public.  
I pulled a csv file for 2018, and then used Openrefine to breakdown/clean up the address column.  
While cleansing the data with Openrefine, I was able to get some ideas of what to analyze.  I used seaborn to visualize the arrest records,
and then used a logistic regression to predict arrests.<br>
The first model uses the features of:<br>
-block number <br>
-street direction <br>
-street name <br>
-street suffix <br>

The second model uses the same features plus the crime code which identifies the type of crime committed.
