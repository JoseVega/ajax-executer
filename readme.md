# Execute script in time intervals

This script allows you to execute a remote script in time intervals.

This is useful if you want to run another script in batches when the server can´t process everything at once.

For example, you have a PHP script that uploads a picture to 50 posts in your blog.
http://sample.com/add-pictures.php?page=1

You have 500 posts so you want to run the PHP script 10 times, one after the other, changing the ?page=N query string to paginate the posts.

You can do this with Ajax Executer.

## Getting Started

* Open the index.html file in your browser. You must open the file from a server, it wont work if you open with the file:// protocol
* Enter the script URL that you want to execute. The iteration number will be appended to the URL, so the URL must have a query string with no value. i.e. http://script.com/?page=
* Select the time interval in miliseconds.
* Enter the "end number" to indicate the maximum number of times to run the script.
* Enter the "end string" if the external script returns a text to indicate completion.
* Enter the "error string" if the external script returns a text to indicate errors.


## Authors

**Jose Vega** - [VegaCorp](http://vegacorp.me)

Some of my projects:
* [WP Sheet Editor](https://wpsheeteditor.com/go/free-plugin-from-github)
