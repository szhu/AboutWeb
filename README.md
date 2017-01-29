AboutWeb
========

This is a simple app designed to silence this dialog:

![error message](doc/error.png)

That's it. That's all it does.


Do you need this app?
---------------------

Browsers are supposed to display the URL `about:blank` as a blank page.
Unfortunately, some web browsers or similar apps do not know how to do this and
will ask macOS to handle this URL. Apps that do this are misbehaving, but until
these apps are fixed, you can use AboutWeb to silence these errors.


Usage
-----

1. [Download this repo](https://github.com/szhu/AboutWeb/archive/master.tar.gz)
   and open it to untar, or `git clone https://github.com/szhu/AboutWeb.git`.
2. You may need to manually open the app once to get rid of the Gatekeeper
   warning. You can do this by right-clicking on the app and selecting Open, or
   by running `cd AboutWeb; bin/un-gatekeeper-ify`.
3. That's it! This app will register itself to open `about:` URLs and will
   handle them by doing nothing.


Uninstall
---------

If you no longer need AboutWeb, just trash the AboutWeb folder or the app.


References
----------

- [rsms/fb-mac-messenger#126](https://github.com/rsms/fb-mac-messenger/issues/126)
