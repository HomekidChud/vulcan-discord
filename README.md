# discord

A Discord-style chat written in pure [Vulcan](https://github.com/HomekidChud/vulcan),
using the 1.16 TCP socket layer (`net_*` builtins). One file, no dependencies,
runs identically on the C, JavaScript and Python backends.

```bash
vulcan add discord
vulcan run . server                          # start the chat server (prints the port)
vulcan run . client 127.0.0.1 <port> alice    # join it
```

Commands: `/nick /join /msg /who /channels /history /help /quit`.
