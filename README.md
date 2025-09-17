# TrackersRemover-Deluge 🗑️

[![Buy me a Coffee](https://img.shields.io/badge/Buy%20me%20a%20Coffee-☕-FFDD00?style=flat-square)](https://www.buymeacoffee.com/Jumitti)

TrackersRemover is a plugin for Deluge that removes trackers from torrents once connections are established. This can be useful for privacy reasons or as an experimental feature, but please be aware of the ethical considerations and potential implications of modifying torrent behavior.

### Disclaimer

Removing trackers from torrents goes against the principles of traditional P2P sharing. By using this plugin, you acknowledge and agree:

- You understand the implications of modifying torrent behavior.
- You are solely responsible for any consequences that arise from using this plugin.
- The author(s) of TrackersRemover are not responsible for any misuse or unlawful use of this software.

### Installation

To install TrackersRemover, follow these steps:

1. **Download the Plugin File:**

   - Go to the [Releases](https://github.com/Jumitti/TrackersRemover/releases) page of this repository.

   - Download the latest `.egg` file for TrackersRemover that matches your operating system and Python version.

2. **Install the Plugin in Deluge:**

   - Open Deluge.
   - Go to Preferences > Plugins.
   - Click on "Install Plugin" and select the `.egg` file you downloaded.
   - Enable "TrackersRemover" from the list of available plugins.
   - Restart Deluge to apply the changes.

#### TrackersRemover Plugin Compatibility

| Plugin File                                                                                         | Deluge Version | Python Version | Compatible Platforms |
|-----------------------------------------------------------------------------------------------------|----------------|----------------|----------------------|
| [```trackersremove-0.1_allremove-py2.7.egg```](https://github.com/Jumitti/TrackersRemover/releases) | 1.3.15         | 2.7            | macOS                |
| [```trackersremove-0.1_py3.7.egg```](https://github.com/besuper/TrackersRemover/releases)           | 1.3.15         | 3.7            | macOS                |
| [```trackersremove-0.1_allremove-py3.7.egg```](https://github.com/Jumitti/TrackersRemover/releases) | 2.1.1          | 3.7            | Windows       |
| [```trackersremove-0.1_py3.7.egg```](https://github.com/besuper/TrackersRemover/releases)           | 2.1.1          | 3.7            | Windows       |


### Usage

Once installed and enabled, TrackersRemover will automatically remove trackers from torrents in Deluge once connections are established. Please note that this behavior is irreversible within the plugin itself.

If you wish to replace trackers with a different set, you can explore the original repository for more options: [TrackersRemover Repository](https://github.com/besuper/TrackersRemover).
