Query reddit and number all unread notifications, can be combined to i3, conky or other programs.

# Before installation

Open up **main.c** and replace the text within the variable **REDDIT\_FEED** with your [own JSON feed](https://github.com/settings/tokens/new?scopes=notifications&description=query-github) ![](https://raw.githubusercontent.com/su8/pinky-bar/master/img/reddit.png)

# Compile

```bash
make
sudo make install
```

# Usages

Just execute `reddit`
