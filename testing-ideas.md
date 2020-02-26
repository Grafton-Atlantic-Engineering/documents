# Testing Ideas

- Check to make sure that the transaction ID is 24 digits and that it is also alpha numeric
- Make around 1000 transaction IDs and go through all of them to make sure there are no duplicates
- Check to make sure that if any of the fields are null such as name or address (more than one field can be null at a time) that the program still makes a transaction ID for a user 
- Test to make sure that if there is a field empty (such as account number) in the csv file that a Person object is still created for each entry in the csv file
