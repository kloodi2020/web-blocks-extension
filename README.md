# Tutorial
## Getting Started
Have you ever wished to be able to do web things in your scratch project?
Well, Wish no longer! This scratch extension lets you do just that!

For a quick start, Go to your favorite scratch mod that has custom extension support!
Then put in this URL: https://kloodi2020.github.com/webBlocks.js, And it will do its thing!
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

![image](https://github.com/user-attachments/assets/11d1cd50-1b59-4357-bd01-b3f57991cd99)

This block fetches data from a URL.
When testing, I found that it usually does the same action as sending a GET HTTP request.

![image](https://github.com/user-attachments/assets/dceb76d4-910e-4b69-8587-65e241e866d0)

This block sends an HTTP request to a URL, With a specific method and body.

![image](https://github.com/user-attachments/assets/2cfa2376-c899-4a1d-8961-a0a2c54cad17)

This block gets a value from a JSON string corresponding to a key.
The whole reason you can read JSON strings at all is with this block.

![image](https://github.com/user-attachments/assets/3f91edc3-aebe-48ca-828d-b5f93e35b291)

This block creates a JSON string that contains a key and a value.

![image](https://github.com/user-attachments/assets/836f4590-b123-469d-bf90-c10710b08726)

Adds the keys and values of two JSON strings together. Useful if you want to create JSON strings with multiple values.
