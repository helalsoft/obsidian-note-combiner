# Note Combiner for Obsidian

A simple plugin to combine all markdown files within a specific folder into a single note.

## Features

- **Combine Notes**: Merges all `.md` files in a selected folder into one master file.
- **Customizable Output**: Choose where to save the combined file (Vault relative or absolute path).
- **Flexible Naming**: Define your own file name template with date and folder name placeholders.
- **Filtering**: Exclude specific files using glob patterns.
- **Content Separation**: Clearly marks the start and end of each original note in the combined file.

## How to Use

1.  **Right-click a folder** in the file explorer and select **Combine notes**.
2.  Alternatively, use the command palette (`Ctrl/Cmd + P`) and run **Combine notes from folder**.
3.  Confirm or edit the destination path in the popup modal.

## Settings

-   **Exclude Glob Pattern**: Ignore files matching a specific pattern (e.g., `**/Secret/**`).
-   **Default Export Path**: Set a default location for generated files.
-   **File Name Template**: Customize the output filename. Supported placeholders:
    -   `{foldername}`: Name of the source folder.
    -   `{date}`: Current date (format customizable).
    -   `{YYYY-MM-DD}`: Custom moment.js date format.
-   **Date Format**: Define the format for the `{date}` placeholder.

## Installation

1.  Download the latest release.
2.  Extract the files into your vault's `.obsidian/plugins/obsidian-note-combiner/` folder.
3.  Reload Obsidian and enable the plugin in Community Plugins settings.
