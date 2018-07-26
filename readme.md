

Delete all the Emails from Gmail that match a search keyword.

## Why?

You cannot delete tens of thousands mails at once on Gmail UI. It will fail at last. So I write a script to do that.

## Usage

1. Install Google client library: `pip install --upgrade google-api-python-client oauth2client`.
2. Goto [Gmail's Python API quickstart page](https://developers.google.com/gmail/api/quickstart/python), click "ENABLE THE GMAIL API" button. Put the downloaded `credentials.json` file in the same directory of this project.
3. Run `python del_mail.py`, it will open a webpage. Login to Gmail and click agree.
4. Input the keyword you want to delete. The script will show some mails that match the keyword. Press enter will delete all the mails that match the keyword.

