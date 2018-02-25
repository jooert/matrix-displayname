# matrix-displayname

This is just a small Python script to set a displayname for just one Matrix room
until support is implemented in major clients (see [this tracking issue for
Riot/Web](https://github.com/vector-im/riot-web/issues/2458)).

## Usage

```
./set_displayname !asfLdzLnOdGRkdPZWu:example.org "John Doe" @johndoe:example.org [password]
```

The script takes three positional arguments: the Matrix room ID, the displayname
to be set and the Matrix ID (MXID) for the user whose displayname you want to
set. You may also supply the user's password as the fourth positional argument;
if you do not the script will prompt for the password.

## Licensing

The code in this project is licensed under the MIT license.
