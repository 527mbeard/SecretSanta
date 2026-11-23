# POST Notes

Partners:

Answer in your own words, 1–3 sentences each.

1. How is a GET request different from a POST request?
    The GET method take information from the google sheet and puts it into the website. It asks for data and it uses doGet(e). The post method sends data and the data goes in the body of the request. Post uses doPost(e).

2. What is the `body` of a fetch() request, and why does it need `JSON.stringify()`?
    The body of the fetch() request is the bundle of data the website sends and JSON.stringify converts the JS into plain text to go into the sheet.

3. What does `doPost(e)` do with the data you send?
    Do Post (e) receives the data and passes it along to the google sheet to create more rows of information.

4. How does your page know the data was saved?
    The page knows the data was saved by reading the server's HTTP response returned after the post request finishes. They will give back status codes depending on if the information was sent or if there is an error. 

## Links we used
