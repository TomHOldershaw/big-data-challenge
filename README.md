# big-data-challenge

Homework submission for week 22

This homework uses published Amazon review datasets to produce a database containing details of those reviews.

Two separate files are processed, with each following the same steps.
- Luggage: reviews in the luggage category
- Pet Products: reviews in the pet products category

Analysis carries out the following steps:
1. Loads data from AWS
2. Produces four separate tables with the following features:
   - Table columns match specified schema
   - Duplicate rows removed where appropriate to avoid Primary Key clashes
3. Loads tables to RDS database

All files are in the 'level-1' folder. The optional part of the homework, 'level-2' has not been submitted.
