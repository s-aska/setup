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

## Daily mecab-ipadic-neologd update

See: https://github.com/neologd/mecab-ipadic-neologd/blob/master/README.md

```
ln -s $HOME/mecab-ipadic-neologd/bin/install-mecab-ipadic-neologd /usr/local/bin/

# Registration
launchctl load setup/launchd/neologd.plist

# Cancellation
launchctl unload setup/launchd/neologd.plist

# Check
launchctl list mecab.ipadic.neologd
```

