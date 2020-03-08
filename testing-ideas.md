# Testing Ideas

- Check to make sure that the transaction ID is 24 digits and that it is also alpha numeric -> done!
- Make around 1000 transaction IDs and go through all of them to make sure there are no duplicates -> done!
- Check to make sure that if any of the fields are null such as name or address (more than one field can be null at a time) that the program still makes a transaction ID for a user -> done!
- Test to make sure that if there is a field empty (such as account number) in the csv file that a Person object is still created for each entry in the csv file and that a transaction ID is still created for them
- Fails if invalid CSV file is given
