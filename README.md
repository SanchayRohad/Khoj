# Khoj
Created a wrapper Python script, that will run the test Python code, to check for errors. It’ll simply print "No errors found", in case there are no syntactic or runtime errors.

On encountering an error, it’ll extract the required error type and the error message.

Then made a REST API call to Stack Exchange API.

From the JSON response obtained, I extracted at most N number of links to Stack Overflow threads and open the same in a web browser.
Tools used:- Python, Stackexchange-API, Http, Rest
