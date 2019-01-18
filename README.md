# Diaspora for Franz 5

This is the [Franz](https://meetfranz.com/) 5 recipe for Mastodon.

The code is just boilerplate generic Franz-recipe stuff. It's copied from https://github.com/sharkpp/franz-recipe-mastodon and modified to work with Diaspora.

## REQUIRED

* [Franz](https://meetfranz.com/) 5 or later
  Do not support older version.
* [Diaspora](https://diasporafoundation.org/) account
  Do not have an account?
  Choose from "[Diaspora Pods](https://podupti.me/)"!
  Note that you can read/follow users from other pods, so your choice of pod isn't all that crucial. Just pick one with a TOS with which you agree.

## HOW TO INSTALL

### DEVELOP VERSION

1. download the `franz-recipe-diaspora` folder.
2. Open the Franz Plugins folder on your machine (note **that this `dev` directory may not exist yet, and you must create it**):
  * Mac: `~/Library/Application Support/Franz/recipes/dev/`
  * Windows: `%AppData%\Franz\recipes\dev\`
  * Linux: `~/.config/Franz/recipes/dev`
3. Copy the `franz-recipe-diaspora` folder into the plugins directory
4. Reload Franz

See [Franz Recipe Documentation / Overview](https://github.com/meetfranz/plugins/blob/master/docs/integration.md)
 for details.

## USAGE

### ADD NEW SERVICE

Click the Add Service (+) button. If Franz recognizes you have a \dev\ folder, you should have a "Development" tab containing the recipe.

### SETTINGS

In the "Service Name" field, add whatever name you want to call your tab.

In the "Team" field, add the URL of your Diaspora pod minus the "https://".

### SIGN-IN

Just sign into the pod as normally.

## LICENSE

&copy; 2018 John Hattan

This software is licensed under a [The MIT License](http://opensource.org/licenses/MIT). Feel free to do what you want with it.
