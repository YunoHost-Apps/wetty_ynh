### Configuration

There is few configuration in Wetty:
* Startup config (listen port, URL path, SSH host) is contained in the systemd service file
* User interface configuration is done through the web GUI itself.

* You need to manually log in.
* You can log in as a specific user using `https://__DOMAIN__/wetty/ssh/<username>`

* You can specify at install if Wetty should be visible by users not logged into YunoHost.

* You can't use SSH key authentication.
