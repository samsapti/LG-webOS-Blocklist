# LG webOS Blocklist

This is a DNS blocklist that attempts to block ads, tracking and
recommendations on LG webOS TVs. The blocklist attempts to avoid as much
breakage as possible, meaning it ONLY blocks stuff that doesn't break normal
functionality and features of webOS. The blocklist only blocks what's left
after disabling as much tracking in the settings as possible, meaning you're
expected to have gone through your TV settings and disabled as much as possible
before using this list.

The list is written in ABP syntax, so it's compatible with newer Pi-hole
versions.

To use it, add
[this link](https://raw.githubusercontent.com/samsapti/LG-webOS-Blocklist/main/list.txt)
to your ABP-compatible ad-blocker, or copy it below:

```txt
https://raw.githubusercontent.com/samsapti/LG-webOS-Blocklist/main/list.txt
```

## Contributing

Contributions are very welcome, as I'm only able to test this on my own setup.
Yours might differ.

## License

This list is published under the MIT license.
