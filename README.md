# Jupyter themes - preview

# Purpose
Trying out new Jupyter notebook themes without manually needing to install new css files. Once new css file is activated in the notebook, that style will be applied.

Once a style/css is installed, it's easy to activate from any notebook using the same `HTML(open('/path/to/profile/custom.css', 'r').read()))` command.


# Usage

Find the URL of the `.css` for a theme that you like and decide on a name for the new profile. Then execute like this:
`mynewstyle(new_style_url, profilename="newprofile_34")`

Here `new_style_url` contains the URL to the `.css` you'd like to use and `profilename` holds the name of the profile (arbitrary).

# Notebook execution demo

![gif of notebook execution](https://i.imgur.com/BPJGygw.gif)

