<!--
N.B.: This README was automatically generated by <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
It shall NOT be edited by hand.
-->

# Fail2Ban Webinterface for YunoHost

[![Integration level](https://dash.yunohost.org/integration/fail2ban-web.svg)](https://ci-apps.yunohost.org/ci/apps/fail2ban-web/) ![Working status](https://ci-apps.yunohost.org/ci/badges/fail2ban-web.status.svg) ![Maintenance status](https://ci-apps.yunohost.org/ci/badges/fail2ban-web.maintain.svg)

[![Install Fail2Ban Webinterface with YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=fail2ban-web)

*[Read this README in other languages.](./ALL_README.md)*

> *This package allows you to install Fail2Ban Webinterface quickly and simply on a YunoHost server.*  
> *If you don't have YunoHost, please consult [the guide](https://yunohost.org/install) to learn how to install it.*

## Overview

That app allow you to monitor Fail2Ban and its jails.

In the web interface you can also manually ban / release IP's.


**Shipped version:** 1.2~ynh1

## Screenshots

![Screenshot of Fail2Ban Webinterface](./doc/screenshots/screenshot.jpg)

## Documentation and resources

- Upstream app code repository: <https://github.com/ewilly/fail2ban-web-interface-php>
- YunoHost Store: <https://apps.yunohost.org/app/fail2ban-web>
- Report a bug: <https://github.com/YunoHost-Apps/fail2ban-web_ynh/issues>

## Developer info

Please send your pull request to the [`testing` branch](https://github.com/YunoHost-Apps/fail2ban-web_ynh/tree/testing).

To try the `testing` branch, please proceed like that:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/fail2ban-web_ynh/tree/testing --debug
or
sudo yunohost app upgrade fail2ban-web -u https://github.com/YunoHost-Apps/fail2ban-web_ynh/tree/testing --debug
```

**More info regarding app packaging:** <https://yunohost.org/packaging_apps>
