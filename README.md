# Gmail SMTP Python

Learn how to use Gmail SMTP server to send emails to users with Python. The process is simple and does not necessitate any external dependencies. Accompanying this repository is a YouTube tutorial, accessible [here](https://youtu.be/aYrd7EGNOlQ).


## Customization
To modify both the sender and receiver email addresses, you can make the change in this cell of the notebook:

```python:
sender_email = ''
sender_password = ''
receiver_email = ''
```

Note that the `sender_password` is not the password you use to connect to your Google account. It's a password, that you need to generate, watch the tuorial, to see how to do that.

Changing the subject as well as the body is straightforward :

```python
subject = "Test Email"
body = "This is a test email"
```