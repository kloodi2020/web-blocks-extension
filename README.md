# Tutorial
## Getting Started
Have you ever wished to be able to do web things in your scratch project?
Well, Wish no longer! This scratch extension lets you do just that!

For a quick start, Go to your favorite scratch mod that has custom extension support!
Then put in this URL: https://kloodi2020.github.io/webBlocks.js, And it will do its thing!
And then you can start using it's blocks! If you don't understand a certain block, You can always count on this README to tell you!

Okay, Now that we are done with that, Let's get started!
This part of the README will just show you a couple of examples while explaining them!
### Getting the weather at a station
We can fetch data from api.weather.gov to get the weather at a station!
The URL to fetch from should be this:
https://api.weather.gov/stations/{STATION}/observations
In this example, I set the station to KNYC. At the time of screenshotting this,
The weather was Cloudy.

![image](https://github.com/user-attachments/assets/044552f8-a102-4c23-b2f5-ecc9934ed24a)

You can replace the station if you want.

# Extension Reference

![image](https://github.com/user-attachments/assets/b25b44d7-3e1f-4e86-92af-b8d543349e3c)

Fetches data from a URL.
When testing, I found that it usually does the same action as sending a GET HTTP request,
Just without the body.

![image](https://github.com/user-attachments/assets/88aa35d8-2c38-4591-b15a-8cc897cbe36f)

Sends an HTTP request to a URL, With a specific method and body, And returns the response.

![image](https://github.com/user-attachments/assets/2cfa2376-c899-4a1d-8961-a0a2c54cad17)

Gets a value from a JSON string corresponding to a key.
The whole reason you can read JSON strings at all is with this block.

![image](https://github.com/user-attachments/assets/3f91edc3-aebe-48ca-828d-b5f93e35b291)

Creates a JSON string that contains a key and a value.

![image](https://github.com/user-attachments/assets/8f4b249b-607c-4296-b45d-1b006e73f017)

Adds the keys and values of two JSON strings together. Useful if you want to create JSON strings with multiple values.
If both JSON contain the same key, The value of the second JSON will overwrite the first JSON.

![image](https://github.com/user-attachments/assets/069c64ca-3a03-437f-8908-651a0497c3e8)

Gets the code from the last HTTP request.

## HTTP Codes
```
1xx: Information
100 = Continue
101 = Switching Protocols
103 = Early Hints

2xx: Successful
200 = OK
201 = Created
202 = Accepted
203 = Non-Authoritative Information
204 = No Content
205 = Reset Content
206 = Partial Content

3xx: Redirection
300 = Multiple Choices
301 = Moved Permanently
302 = Found
303 = See Other
304 = Not Modified
307 = Temporary Redirect
308 = Permanent Redirect

4xx: Client Error
400 = Bad Request
401 = Unauthorized
402 = Payment Required
403 = Forbidden
404 = Not Found
405 = Method Not Allowed
406 = Not Acceptable
407 = Proxy Authentication Required
408 = Request Timeout
409 = Conflict
410 = Gone
411 = Length Required
412 = Precondition Failed
413 = Request Too Large
414 = Request-URI Too Long
415 = Unsupported Media Type
416 = Range Not Satisfiable
417 = Expectation Failed

5xx: Server Error
500 = Internal Server Error
501 = Not Implemented
502 = Bad Gateway
503 = Service Unavailable
504 = Gateway Timeout
505 = HTTP Version Not Supported
511 = Network Authentication Required
```
