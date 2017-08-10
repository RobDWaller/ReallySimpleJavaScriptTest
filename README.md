# Really Simple JavaScript Test

A simple data manipulation and styling test for front end developers. There are
numerous ways to complete the tasks involved in this test and there are no right,
or perfect answers. The test though will reveal roughly how knowledgeable and
experienced a front end developer is.

## The Test

This test aims to see how well a front end developer understands JavaScript data
manipulation and how well they can style HTML output.

The test is based on a JSON object that is broken down into child objects and
arrays. This object is stored in the `./assets/js/test-data.js` file.

Your JavaScript code for manipulating the data and passing it to the DOM should
be written in the file `./assets/js/test-script.js`.

Any written or generated CSS should appear in the file `./assets/css/style.css`.

### The JSON Object

```javascript
{
    "users": {
        "metaData": [
            {
                "id": 4325,
                "name": "James Jones",
                "username": "jj92",
                "email": "jj92@gmail.com",
                "dob": "04-03-1992",
                "created_at": "01-09-2014 09:13:25"
            },
            {
                "id": 7431,
                "name": "Sarah Simons",
                "username": "ssimons729",
                "email": "s.simons729@gmail.com",
                "dob": "13-03-2001",
                "created_at": "11-02-2017 13:20:01"
            }
        ],
        "metricData": [
            {
                "id": 7431,
                "last_login": "07-08-2017 16:33:02",
                "login_count": 501,
                "comment_count": 11,
                "like_count": 798
            },
            {
                "id": 4325,
                "last_login": "07-08-2017 19:29:43",
                "login_count": 243,
                "comment_count": 53,
                "like_count": 109
            }
        ]
    }
}
```

### The Tasks

- Display the user data stored in `./assets/js/test-data.js` in the index.html file.
- The displayed data should be placed inside the div with the id `#test-data`.
- The displayed data should include the fields: id, username, email, comment count,
like count, like count per login count, and created at.
- You will have to calculate the like count per login count field based on existing
data fields.
- The data should be ordered by the calculated field like count per login count
in descending order.
- Please style the outputted HTML so it looks presentable and so it can be viewed
on a mobile device.

### Additional Information
There are no rules on how you should complete this task, nor are there any
restrictions on what libraries you can and cannot use to complete this task.  

Also feel free to style the displayed data as you see fit. In addition there are
no rules defining whether you can tools like SASS or LESS to generate CSS.

## Notes for Interviewers

If you would like to use this test for interviewing candidates we advise that it
is used in the following ways.

- This test should go hand in hand with an actual interview, it should not be
used as a filter.
- Candidates should be made aware that they will not be assessed based on this
test alone.
- Advise candidates they should not spend more than 30-60 minutes on this test
regardless of whether they complete it or not.

## Authors

Rob Waller

Twitter: (@robdwaller)[https://twitter.com/robdwaller]

## License

MIT
