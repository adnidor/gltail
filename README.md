# gltail

## How to use:

Copy to a location in your `$PATH`.

Create a config file in `~/.config/gltail.conf` containing

```
[gltail]
hostname = $your-hostname
port = $your-port
secure = $do-you-use-https?
```

and either 

```
access_token = $your-access-token
```

or

```
username = $your-username
password = $your-password
```

If you enter username and password `gltail` will generate an access token on the first run and replace the username/password fields.

## Known Bugs

When using --follow it errors out sometimes, no idea why. Help welcome.
