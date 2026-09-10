# Homebrew tap

Install remotefs, a read-only browser for local folders, SMB shares and NFS exports:

```sh
brew install mightymorgs/tap/remotefs
remotefs serve
```

To run it in the background, use `brew services start remotefs`. Show the sign-in token with `remotefs --print-token`.

[Project documentation](https://github.com/mightymorgs/remote-fs-browser)
