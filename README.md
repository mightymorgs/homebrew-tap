# Homebrew tap

Install remotefs to browse and manage local folders, SMB shares and NFS exports:

```sh
brew install mightymorgs/tap/remotefs
remotefs
```

The interactive setup detects your networks and helps you configure access and a username and password. Run `remotefs setup` to revisit setup.

To upgrade an existing installation:

```sh
brew update
brew upgrade mightymorgs/tap/remotefs
```

After setup, use `brew services start remotefs` to run it in the background.

[Quickstart](https://mightymorgs.github.io/remote-fs-browser/quickstart.html)
