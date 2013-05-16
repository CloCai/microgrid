microgrid
=========


Data files
----------

1. Circuit_1.csv
2. Circuit_2.csv
3. Circuit_3.csv
4. Circuit_4.csv
5. Circuit_5.csv
6. Circuit_6.csv
7. Circuit_7.csv
8. Circuit_8.csv
9. Circuit_9.csv
10. Circuit_10.csv
11. Circuit_13.csv
12. Raw Hourly Until 2012 Nov 2 - queen_0003_WH_Fri Nov 02 2012 08-04-56 GMT-0700 (PDT).xls

Coding Files and instructions
-----------------------------

1. apriori.py

   Run the code with the data file aprioridata.csv to generate the association rules

    Usage
      $python apriori.py -f DATASET.csv -s minSupport  -c minConfidence

    Eg.
  	    $ python apriori.py -f aprioridata.csv -s 0.15 -c 0.6
      
    Results in aprioriresults.txt
    
2. DataMining_Project.ipynb
   
   Using K means and Regression to cluster a set of 11 users and predict the usage behaviour of a new user data

  Resultant graphs and illustrations are generated in the ipython notebook 


Graphical clustering result
---------------------------
1. User_Watt_Usage.png
