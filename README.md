# RSS Reader - LB Extension
This extension for Lioranboard can fetch a RSS feed so you can use its information for overlays etc.

## Usage
The extension will create 3 stacks after fetching the RSS feed, these stacks will be prefixed with the name of your choosing.
For example if you provide the name **bbc** as the Stack Name in the `Send to Extension` command, you'll get to following 3 stacks:
- `bbc:titles`
- `bbc:descriptions`
- `bbc:links`

The latest feed entry will be located at index 0 in each stack.

**Note:** in most cases you'll need to set the CORS option to `Yes`.

## Download
To download the extension visit the [release](https://github.com/WaldoAndFriends/lb-rss-reader/releases) section and grab the `.lbe` file from the latest release.
