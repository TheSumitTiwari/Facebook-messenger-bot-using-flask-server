# Facebook messenger bot using flask server

Being able to automate stuff and make useful bots in Facebook messenger appears to be interesting and cool, in this project, we have connected Facebook messenger with Flask server.

## Getting Started

Firstly you need to Setup Facebook Developer Account on [Meta for Developers](https://developers.facebook.com/), Then create a Facebook App & Facebook page, and set it all up.
Fetch your PAGE_ACCESS_TOKEN and also add a VERIFY_TOKEN. [Click on this link for detailed tutorial.](https://developers.facebook.com/docs/messenger-platform/getting-started/quick-start/)

### Installation

Download or Clone the repo, Navigate to the directory containing the files and run
` python app.py install` to install the dependencies.
` python app.py` to run the project.

### Use

Copy your PAGE_ACCESS_TOKEN and VERIFY_TOKEN and insert in `app.py` where specified.
Use [ngrok](https://ngrok.com/) to expose local webserver to the internet so that it can be used for callback verification needs to be done for using a webhook with facebook app.

Final project can be found here [MP Travel and Tourism Facebook Chatbot](https://github.com/TheSumitTiwari/MP-Travel-and-Tourism-Facebook-Chatbot)
