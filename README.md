# praw-stream-keyword-example

A simple example of how to scan Reddit's comments for keywords using PRAW, send an e-mail when a comment is found, and add the results to a log file.

To use:

1) Set up an app on Reddit here <A HREF="https://www.reddit.com/prefs/apps/">https://www.reddit.com/prefs/apps/</A>.  Hit Create App.  

<IMG SRC="https://i1.wp.com/pythonforengineers.com/wp-content/uploads/2014/11/redditbot2.jpg" />

2) Put the client id (red box above) in praw.ini as client_id, and client secret (blue box above) in praw.ini as client_secret.

3) Edit the config.py file to set up an SMTP server with which to send mail.

4) RUN


Note:  this example uses a custom Python install at <strong>#!/usr/local/bin/python2.7</strong>.  Edit this location on line 1 of the script to match your Python binary.
