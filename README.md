# setup

## first step
```
git clone git@github.com:s-aska/setup.git
```

## daily brew update
```
# registration
launchctl load setup/launchd/brew.plist

# cancellation
launchctl unload setup/launchd/brew.plist

# check
launchctl list sh.brew
```
