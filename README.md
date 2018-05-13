# weed - XChat based theme for irssi

[![GitHub contributors](https://img.shields.io/github/contributors/x70b1/irssi-weed.svg)](https://github.com/x70b1/irssi-weed/graphs/contributors)

This is an updated version of [ronilaukkarinen/weed](https://github.com/ronilaukkarinen/weed). All congratulations go to him. Primarily the scripts have been updated. However, some of the config had to be adapted to this.

I have added `smartfilter.pl`.


## Usage

```
settings = {
  core = {
    real_name    = "";
    user_name    = "";
    nick         = "";
    quit_message = "bye!";
    }
  };

servers = ();

chatnets = {};

channels = ();
```

* Change your username and your quit message in your `config` file. You can add the snippet from above to your config.
* Adapt your `config` further to your requirements.
* Start chatting around.


## The following scripts are used:

* adv_windowlist.pl
* nickcolor_expando.pl
* smartfilter.pl
* trackbar22.pl

Look into the `perl/core/scripts` area in the `config` file. The settings for the scripts are set there.

Check also the `startup` file.
