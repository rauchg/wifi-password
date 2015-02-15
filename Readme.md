
# wifi-password

People ask you for the Wi-Fi password. Answer quickly. **OSX only**.

Check out [RReverser/WiFi-Password](https://github.com/RReverser/WiFi-Password) for Windows analog.

![](https://i.cloudup.com/uUo8iSbKXRh/km6iJT.gif)

## How to use

**1. Install it**

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

## License

MIT
