# dotfiles

## Ruby
### Install Ruby with rbenv
```
rbenv install 2.5.3
```

### Installing Nokogiri
```
bundle config build.nokogiri --use-system-libraries=true --with-xml2-include="$(xcrun --show-sdk-path)"/usr/include/libxml2
```