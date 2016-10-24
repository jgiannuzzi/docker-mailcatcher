# Docker image for [MailCatcher](https://mailcatcher.me), a simple SMTP server which catches any message sent to it to display in a web interface.

Based on [Alpine Linux](http://alpinelinux.org/).

Patched to:

- persist mails to a volume
- fix issues with UTF-8 encoding
