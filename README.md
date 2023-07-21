# script
writing a test script for an API in postman, the test is checking to see the api responses based on the JSON data, in this case its for the type (one of the key-value pairs in the json data).  

Example:
{
    "activity": "Learn to sew on a button",
    "type": "education",
    "participants": 1,
    "price": 0.05,
    "link": "",
    "key": "8731971",
    "accessibility": 0.1
}

The test would fail for this as the "type" is not equal to cooking, but the test would pass if it did.
