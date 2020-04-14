# Disclaimer
This is just a tool I've built in an afternoon and I am no Python expert. Things could probably be done in a much more nicer Pythonic way.

# gmail_extractor
A Python powered Gmail mailbox extractor tool. Use this to extract all emails and attachments of a Gmail mailbox.

# How it works
This is a simple, quickly developed tool to allow extraction of emails from a Gmail mailbox onto your local computer. This tool will extract some default information such as "subject", "date" and "from" into a convenient JSON format as well as all the attachments available in the email. Afterward, it will store all this into a folder with the UID of the email as its name.

# How to run
Just do python3 gmail_extractor.py. Make sure you are using a version of Python > 3.7.5 even if this could work with Python 3.3 or greater.

