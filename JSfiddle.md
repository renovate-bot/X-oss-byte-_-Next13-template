Pass response directly from a Github repo
While the demo might use an Async requests, JSFiddle will read them and send using the right MIME type.
Demo directory structure
Demo Directory/
  demo.response.html
  demo.response.json
  demo.response.xml
Running demo in JSFiddle
https://jsfiddle.net/gh/get/response.{extension}/{github_tree}/
URL segments in examples:
extension – the file extension of the demo.response.{extension} in github demo repository.
github_tree – the path to the directory used to display it on github page (without http://github.com/).
There is no JSONP functionality provided. One may achieve it using raw GitHub URL.
Example
Content of:
http://github.com/zalun/jsFiddleGithubDdemo/raw/master/Demo/demo.response.html
will be returned with text/html MIME type if this URL will be loaded from:
https://jsfiddle.net/gh/get/response.html/zalun/jsFiddleGithubDemo/tree/master/Demo/
Example: 
​http://jsfiddle.net/gh/get/mootools/1.2/zalun/jsFiddleGithubDemo/tree/master/Demo/​
Previous
Display fiddle from Gist
Next
Pass response directly from Gist
