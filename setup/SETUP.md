# Setup Rust
## 1. Install Rust on Macos

```
curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh
```

If you encounter the error like
```
error: could not amend shell profile: '/Users/XXXX/.bash_profile'

could not write rcfile file: '/Users/XXXX/.bash_profile'

Permission denied (os error 13).
```

Please follow [here](https://stackoverflow.com/questions/71986942/getting-error-could-not-amend-shell-profile-permission-denied-installing-rus)