### Configuration

There is few configuration in Wetty:
* Startup config (listen port, URL path, SSH host) is contained in the systemd service file
* User interface configuration is done through the web GUI itself.


* Is LDAP and HTTP authentication supported? **No**
  * You need to manually log in.
  * You can log in as a specific user using `https://<host>/wetty/ssh/<username>`

* You can specify at install if Wetty should be visible by users not logged into YunoHost.

* You can't use ssh key authentication.
