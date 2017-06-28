# STAD

A program written for involvement with Stillwater Labs, as phase 2. Intended to interact with Shimadzu hardware (to start) and feed data into a central database, likely MongoDB. This will also have to forward data along to a website for customer presentation and generate reports. 

1. Scales/Moisture analyzers
   1. Read data directly from a scale onto a raspberry pi
   2. Collate that data into a central location (csv or sqlite database) 
   3. Present that data in a verifiable webpage to be used by another program later on.
2. Database
   1. Read Shimadzu generated .csv files into the database.
   2. Combine those files with data read from scales and other sources (pictures, observations, notes, etc.). 
   3. Allow final data to be selected for processing.
   4. Generate a final report to be passed along to website/email/customer.
