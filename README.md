# Welcome to Snake.

> Snake is basically a web crawler put into a PyQt5 Framework. The software is completely > written by me. Just for fun to be honest with you. Normally people write documentation for their software, so this is my attempt. Just know the software is in early development.

"Snake" has a build in text editor to make life easy. Slide with you buddy "Python3.7" like a snake through the data the internet offers and save it right away to your system. Or as a text editor suggests edit your fetch!

### Features 

###### Tools
> - Editor
> \
> Build in Snake is a quick and simple text editor. You are able to copy the output of for example the scraper and paste it directly into your editor.
> - Save/Load file
> \
> A editor is not a editor if its not able to save and open files.
> - Scraper
> \
> Fetch hyperlinks across webservers. webservers may contain valuable data such as scripts or maybe links to unsecure admin pages, who knows. This function searches for navigatable links on a single page. The links found on the page are getting sorted out and run through the scraper once more. With a little bit of magic and a bit of believe a clean ordered output rolls out.
> - Decoder
> \
> Decode **Base64** and **ROT13** to readable text.

###### Settings
> - Change the font of the program.
> \
> You have the possibility to change the font of the program. Increase the size of the font or even change the color!
> - Window Style
> \
> Along the years we had a hand full of styles we could choose from on a system. This changed your theme of your computer to your personal preferences.You can choose between any style available on your machine.

###### New Updates
> Snake lets you know when there is a new version available to download. Because this is a opensource project, there will be a chance someone uses my code which is fine by me but because this feature is implemented, I want you to know that I (the creator) only upload at:
> - https://github.com/Annihilator708/Snake
> - https://www.codewars.nl/
>
> Do not be foolish and download malware.

### Future
The future is very bright for this program. I got a couple of ideas which I like to try out and implement this in Snake. When I'm done, I expect to have developed a great toolbox which contains tools to make everyday tasks just a slightly more easy/enjoyable.

### Contribution
Ideas and requests are greatly appreciated. If you have any ideas please feel free to use the template "feature_request_template" provided in the **documentation** folder

### Bugs
Like wise Contribution there is a bug template available in the **documentation** folder. Feel free to create a ticket with your problem or contribute to solve the issue. Don't forget to make a pull request!

## Installation
Make sure you have python3.7 installed. **This program will not work on python 3.6 <**. How ever you like to use python, I like to create a virtual env. I suspect you know what you are doing. So here we go. I always put my virtualenv in the project folder and call it venv. You can call it however you like.
```
virtualenv venv
```
After this is done make sure you have your virtual env **activated**. Install the **requirements.txt**.
```
python -m pip install -r requirements.txt
```
After this you are all set!, Start **Snake** with the following command:
```
python main.py
```

> ##### More documentation? [Yes, you rock!](https://github.com/Annihilator708/Snake/blob/master/.github/Documentation/DOCUMENTATION.MD)