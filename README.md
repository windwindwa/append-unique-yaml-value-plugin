# Append Unique YAML Value Plugin for Obsidian

Automatically append new values from a YAML field to the end of your Markdown files in Obsidian, ensuring that duplicates are not added.

中文： 根据yaml字段中指定key，获取value。 每新增一个value，在文件末尾同步追加这个 value（我计划是### value，这个格式）
## Overview

This plugin enhances your Obsidian experience by monitoring changes to a specified YAML field within your Markdown files. When a new value is added to the field, the plugin appends it to the end of the file. If the value already exists in the file, the plugin does nothing, avoiding unnecessary duplication.

## Features

- **YAML Field Monitoring**: Monitors changes to a specified YAML field.
- **Unique Value Appending**: Appends new values to the end of the Markdown file.
- **No Duplicates**: Prevents appending values that already exist in the file.
- **Effortless Integration**: Works automatically with no manual intervention required.

## Installation

1. **Download the Plugin**: Get the latest release of the plugin from the [releases page](#).
2. **Place in Plugins Directory**: Copy the `AppendUniqueYamlValuePlugin` folder into your Obsidian plugins directory, usually located at `.obsidian/plugins/`.
3. **Restart Obsidian**: Restart Obsidian for the plugin to take effect.

## Usage

The plugin operates automatically in the background. Here's how it works:

1. Open and edit a Markdown file with a YAML block.
2. Add a new value to the specified YAML field.
3. Save the file.
4. The plugin detects the change, checks if the value already exists in the file, and if not, appends it to the end.

### Notes
This is a test version for my self, so if want to use it, should modify the source code by your self.

## Configuration

- **Field Name**: The plugin is designed to monitor a specific YAML field. You will need to modify the source code to change the field it tracks. Replace `'your-specific-field'` in the source code with the actual field name you wish to monitor.
- **Value Placement**: New values are appended under a section titled "新增的值". You can customize the title and formatting in the source code.

## Compatibility

This plugin is compatible with Obsidian version 0.12.0 and above.

## Support

If you encounter any issues or have suggestions for improvements, please [open an issue](https://github.com/windwindwa/append-unique-yaml-value-plugin/issues) on the plugin's repository.

## Contributing

Contributions are welcome! If you'd like to contribute to the plugin, please [fork the repository](https://github.com/windwindwa/append-unique-yaml-value-plugin/releases), make your changes, and submit a pull request.

## License


## Credits

Developed by [me](https://github.com/windwindwa).

---

Thank you for using the Append Unique YAML Value Plugin. Your feedback is greatly appreciated!
