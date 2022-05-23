# soviet-twitter-bot
Twitter Bot for posting soviet / eastern european jokes from raspi

== Requirements ==

- Python 3
- python3-pip
- python3-venv
- tweepy
- dotenv

  apt-get update
  apt-get install python3-pip
  apt-get install build-essential libssl-dev libffi-dev python3-dev
  apt-get install python3-venv
  mkdir tutorial_twitter_bot
  cd tutorial_twitter_bot
  python3 -m venv SOVIET_BOT_ENV
  source ./SOVIET_BOT_ENV/bin/activate
  pip install -Iv tweepy==3.10.0
  pip install python-dotenv
  pip freeze > requirements.txt
