# Lennys' Developer key for Package signing

## To Import in pacman

```sh
# pacman-key --add devkey.pub
```

Check Key ID with
```sh
# pacman-key --list-keys
```

Key ID is: DC3078524947AB88189C7A8B91C147DBB1627F9B

```sh
# pacman-key --lsign-key DC3078524947AB88189C7A8B91C147DBB1627F9B
```

Also set the trust-level of the key

```sh
# pacman-key --edit-key DC3078524947AB88189C7A8B91C147DBB1627F9B
```

Then type `trust` choose trustlevel `4` is okay ;-)
Then type `save`

Cheers!
