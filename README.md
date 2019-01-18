# Diaspora for Franz 5

This is the [Franz](https://meetfranz.com/) 5 recipe for Diaspora.

The code is just boilerplate generic Franz-recipe stuff. In this case, it's copied from https://github.com/sharkpp/franz-recipe-mastodon and modified to work with Diaspora. There is absolutely no magic going on here.

## REQUIRED

* [Franz](https://meetfranz.com/) 5 or later
  This does not work with older versions.
* A [Diaspora](https://diasporafoundation.org/) account. If you need an account, choose one from a list of [Diaspora Pods](https://podupti.me/).
  Note that you can read/follow users from other pods, so your choice of pod isn't all that crucial. Just pick one with a TOS with which you agree.

## HOW TO INSTALL

1. download all of the files into a `franz-recipe-diaspora` folder.
2. Open the Franz Recipes folder on your machine (note **that this `dev` folder may not exist. If it's not there, create one.**):
  * Mac: `~/Library/Application Support/Franz/recipes/dev/`
  * Windows: `%AppData%\Franz\recipes\dev\`
  * Linux: `~/.config/Franz/recipes/dev`
3. Copy the `franz-recipe-diaspora` folder into the recipes\dev folder
4. Reload Franz

See [Franz Recipe Documentation / Overview](https://github.com/meetfranz/plugins/blob/master/docs/integration.md)
 for details.

## USAGE

### ADD NEW SERVICE

After reloading Franz, click the Add Service (+) button. If Franz recognizes you have a \dev\ folder, you should have a "Development" tab containing the recipe.

### SETTINGS

In the "Service Name" field, add whatever name you want to call your tab. Mine is "Pluspora"

In the "Team" field, add the URL of your Diaspora pod minus the "https://". Mine is "Pluspora.com"

### SIGN-IN

Just sign into the pod as normal.

## LICENSE

&copy; 2018 John Hattan

This software is licensed under a [The MIT License](http://opensource.org/licenses/MIT). Feel free to do what you want with it.

<pre>If you want to follow me, my Diaspora name is @johnhattan@pluspora.com</pre>