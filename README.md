# Bard AI Unofficial API

* This API uses Playwright and Chromium to automate a browser and parse responses automatically.
* It is an unofficial API and is intended for development and educational purposes only.

# How to install

* Install the requirements

```
pip install -r requirements.txt
```

* If you are installing Playwright for the first time, please run the below command as well.

```
python -m playwright install
```

* Now run the server

```
python server.py
```

* The server runs at port `5001`. If you want to change, you can change it in server.py

# Login
* Login to your Google account with Bard access once the browser starts. Once you have logged in, the API will be ready to query.

# API Documentation

* There is a single end-point only. It is available at `/chat`

```sh
curl -XGET http://localhost:5001/chat?q=What%20is%20the%20capital%20of%20South%20Carolina?
```

# Updates

* [April 4, 2023]: Initial release


# Credit

This project is by Sean Henry Lewis.
