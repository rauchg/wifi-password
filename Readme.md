
# wifi-password

People ask you for the Wi-Fi password. Answer quickly. **macOS only**.
[Windows version](https://github.com/RReverser/WiFi-Password).

![](https://i.cloudup.com/uUo8iSbKXRh/km6iJT.gif)

## How to use

**1. Install it**

With [bpkg](https://github.com/bpkg/bpkg):

```
$ bpkg install rauchg/wifi-password
```

With [Homebrew](https://github.com/Homebrew/homebrew):

```
$ brew install wifi-password
```

With [Antigen](https://github.com/zsh-users/antigen):

Add `antigen bundle rauchg/wifi-password` to your `.zshrc` with your other antigen commands

With [Zgen](https://github.com/tarjoilija/zgen)

Add `zgen load rauchg/wifi-password` to your `.zshrc` with your other zgen commands

or with `curl`:

```
curl -L https://raw.github.com/rauchg/wifi-password/master/wifi-password.sh -o ~/bin/wifi-password && chmod +x ~/bin/wifi-password
```

If you don't have `~/bin` in your `$PATH`, replace it with `/usr/local/bin` or
similar.

**2. Use it:**

To get the password for the WiFi you're currently logged onto:

```
$ wifi-password
```

To get it for a specific SSID:

```
$ wifi-password <ssid>
```

To put it straight in your clipboard for pasting elsewhere (OS X only):

```
$ wifi-password | pbcopy
```

## License

MIT
