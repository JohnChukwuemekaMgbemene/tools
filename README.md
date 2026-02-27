# Firxttech Toolbelt

A curated collection of tools distributed by [Firxttech](https://firxttech.com/tools). Source code for each tool lives in separate private repositories; this repo is the public distribution point for releases and downloads.

---

## Available Tools

| Tool | Description | Latest Release |
|------|-------------|----------------|
| [OfficeRemover](./tools/OfficeRemover/) | Cleanly removes Microsoft Office installations from Windows | [v0.2.0](https://github.com/JohnChukwuemekaMgbemene/tools/releases/tag/OfficeRemover-v0.2.0) |

---

## Installation

Each tool is distributed as a self-contained binary. Download the appropriate release asset for your platform from the [Releases](https://github.com/JohnChukwuemekaMgbemene/tools/releases) page.

### Quick install (Linux / macOS)

```bash
# Replace <tool-name> and <version> with the desired tool and version
curl -fsSL https://github.com/JohnChukwuemekaMgbemene/tools/releases/download/<version>/<tool-name> -o <tool-name>
chmod +x <tool-name>
sudo mv <tool-name> /usr/local/bin/
```

### Windows

Download the `.exe` asset from the [Releases](https://github.com/JohnChukwuemekaMgbemene/tools/releases) page and place it somewhere on your `PATH`.

---

## Usage

Refer to each tool's individual README located in its subdirectory under [`tools/`](./tools/).

---

## Releases

New versions are published via [GitHub Releases](https://github.com/JohnChukwuemekaMgbemene/tools/releases). Each tool is tagged independently (e.g. `OfficeRemover-v0.2.0`). To publish a new release:

1. Add or update the tool's `README.md` in `tools/<ToolName>/`
2. Push a tag: `git tag <ToolName>-v<version> && git push origin <ToolName>-v<version>`
3. Upload the binaries to the auto-created GitHub Release

---

## Disclaimer

The source code for these tools is maintained in private repositories. Binaries are provided as-is. If you encounter a bug or want to request a feature, please open an [issue](https://github.com/JohnChukwuemekaMgbemene/tools/issues).
