# Static Marks - Bookmark Search

This extension is made to search through your [Static Marks](https://github.com/darekkay/static-marks) bookmark YAML file(s).

## How to use

You can provide either:
- The location of a single [bookmarks YAML file](https://github.com/darekkay/static-marks#file-format) (absolute path or public URL)
- The path to a **folder containing multiple YAML files** (absolute path only)

If you don't have bookmarks YAML files, you can create them from your existing browser bookmarks with the [Static Marks CLI](https://github.com/darekkay/static-marks#quickstart).

### Single file examples:
- **Absolute path**: `/Users/[user folder]/bookmarks.yml`
- **Public URL**: `https://raw.githubusercontent.com/darekkay/static-marks/master/test/examples/maximal-example.yml`

### Multiple files example:
- **Folder path**: `/Users/[user folder]/bookmarks/` (folder containing `work.yml`, `personal.yml`, `news.yaml`, etc.)

When using a folder, the extension will automatically discover and merge all `.yml` and `.yaml` files in the specified directory.
