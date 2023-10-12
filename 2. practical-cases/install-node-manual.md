1. Go to the homepage and download Node

```
  https://nodejs.org/download/release/v18.14.2/
  node-v18.14.2-darwin-arm64.tar.xz
```

2. Put the unpacked file under username directory

```
  `/Users/<username>/Apps/node-v18.14.2-darwin-arm64.tar.xz`
```

3. Set the system environment to `.base_profile` for Node

```
  export PATH="$HOME/Apps/node-v18.14.2-darwin-x64/bin:$PATH"
```

4. Quarantine the entire unpacked folder

```
  xattr -r -d com.apple.quarantine .
```

5. Verify the installation

```
  node -v
```
