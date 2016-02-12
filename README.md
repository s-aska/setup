# Setup

## First step
```
git clone git@github.com:s-aska/setup.git
```

## Daily brew update
```
# Registration
launchctl load setup/launchd/brew.plist

# Cancellation
launchctl unload setup/launchd/brew.plist

# Check
launchctl list sh.brew
```
