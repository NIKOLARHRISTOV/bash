# sdkman plugin

This plugin will automatically source [sdkman](https://sdkman.io/).

## Installation

### Install sdkman

Let's [install the sdkman](https://sdkman.io/install) without updating shell
config!

```sh
$ curl -s "https://get.sdkman.io?rcupdate=false" | bash
```

### Include sdkman as plugin

```sh
plugins=(
	git
	sdkman
)
```
