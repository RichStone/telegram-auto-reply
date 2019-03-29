# Telehandler

Telehandler aims to give a convenient possibility to send your friends an automated message, when you are away from Telegram for some time.


# Installation

1. download the repo
2. activate a venv
3. install the requirements.txt
4. get your API credentials https://core.telegram.org/api/obtaining_api_id
5. add TELEGRAM_API_ID and TELEGRAM_API_HASH to your script or, **much better**, to your environment variables / a secret file


# Usage

```bash
python3 autoreplier.py
```

The Telehandler will run in the background and process new incoming messages with an automated reply.

# Meta

Stability and side effects were not tested so far.

Inspired by this great blog post:

<a href="https://medium.com/@jiayu./automatic-replies-for-telegram-85075f28321" target="_blank">Medium Post by Jiayu Yi</a>
