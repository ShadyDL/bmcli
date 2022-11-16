# BMCLI

Beast Mode CLI

## Getting Started

Add a copy of `bmcli` to `usr/local/bin`.

```sh
./bmcli as_executable
```

Now instead of `./bmcli` you can run `bmcli` from anywhere (when you restart the terminal).

Yup that's it, all done!

## Making changes

When you make changes you also need to update `bmcli` in `usr/local/bin`.

```sh
# Needs to be run from the root of the repo.
./bmcli update
```

## How to use

```
bmcli help
```

## Add a command (Deprecated)

Used to be necessary when commands were separate scripts instead of functions.

```sh
chmod +x ./commands/my_new_command
```

## Sources

- https://thoughtbot.com/upcase/videos/lets-build-a-cli
- https://medium.com/@brotandgames/build-a-custom-cli-with-bash-e3ce60cfb9a4
