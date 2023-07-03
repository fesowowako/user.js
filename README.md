<h1 align="center">fesowowako/user.js</h1>
<p align="center">Removes Mozilla spyware from Firefox and makes Firefox more secure</p>

<br>

## About this user.js

This user.js aims at disabling all Firefox telemetry (spyware), it also hardens the browser, installs uBlock Origin and replaces the spyware search engines with privacy respecting ones.

## How to use (GNU/Linux)

WARNING: This will remove everything from your default profile.

```
git clone https://github.com/fesowowako/user.js
cd user.js
./install.sh
```

Optionally you can remove the default plugins that can violate your privacy

```
sudo rm /usr/lib64/firefox/browser/features/*
```
