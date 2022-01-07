### Load books from DynamoDB

In the previous try activity you wrote and annotated a POJO, `Book`, based on the `DynamoDbAnnotationsLoadSave-Books`
DynamoDB table. Now you're going to take that annotated POJO and write a load method, called `getBook()`, in the
`BookDAO` class. This method should accept as arguments the key schema, load an item from the Books table using
the key value that's passed in, and return the new instance of the `Book` class.

You should have deployed the `DynamoDbAnnotationsLoadSave-Books` table in the previous try. You can view your table
in the AWS Console. Use the table and annotated class to help you write your `getBook()` method.

You can run the `BookDaoTest` tests to verify you have implemented `getBook()` properly.

**You have completed this pre-work when:**
* You have implemented the `getBook()` method in the `BookDao` class.
* The `BookDaoTest` tests are passing.
* You have committed and pushed your code.
* You have answered the Canvas quiz with a link to your commit on code browser.

**HINT:**
* [The getBook() method isn't finding the correct item or giving me an error!](hints/hint-01.md)
* [I don't know how to create a new instance of DynamoDBMapper, help!](hints/hint-02.md)

