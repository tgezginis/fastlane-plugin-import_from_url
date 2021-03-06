# import_from_url plugin

[![fastlane Plugin Badge](https://rawcdn.githack.com/fastlane/fastlane/master/fastlane/assets/plugin-badge.svg)](https://rubygems.org/gems/fastlane-plugin-import_from_url)
[![Build Status](https://github.com/dorukkangal/fastlane-plugin-import_from_url/workflows/build/badge.svg)](https://github.com/dorukkangal/fastlane-plugin-import_from_url/actions)
[![Build Status](https://travis-ci.com/dorukkangal/fastlane-plugin-import_from_url.svg?branch=master)](https://travis-ci.com/dorukkangal/fastlane-plugin-import_from_url)

## Getting Started

This project is a [_fastlane_](https://github.com/fastlane/fastlane) plugin. To get started with `fastlane-plugin-import_from_url`, add it to your project by running:

```bash
fastlane add_plugin import_from_url
```

## About import_from_url

Import another Fastfile from given url to use its lanes.

**Note to author:** Add a more detailed description about this plugin here. If your plugin contains multiple actions, make sure to mention them here.

## Example

```ruby
import_from_url(
  url: "<the url of the Fastfile to be downloaded>", # Required and cannot be empty,
  path: "<the path of the Fastfile to be downloaded>", # Optional and default is fastlane/.cache
  file_name: "<the name of the Fastfile to be downloaded>" # Optional and default is DownloadedFastfile
)
```

## Run tests for this plugin

To run both the tests, and code style validation, run

```
rake
```

To automatically fix many of the styling issues, use
```
rubocop -a
```

## Issues and Feedback

For any other issues and feedback about this plugin, please submit it to this repository.

## Troubleshooting

If you have trouble using plugins, check out the [Plugins Troubleshooting](https://docs.fastlane.tools/plugins/plugins-troubleshooting/) guide.

## Using _fastlane_ Plugins

For more information about how the `fastlane` plugin system works, check out the [Plugins documentation](https://docs.fastlane.tools/plugins/create-plugin/).

## About _fastlane_

_fastlane_ is the easiest way to automate beta deployments and releases for your iOS and Android apps. To learn more, check out [fastlane.tools](https://fastlane.tools).
