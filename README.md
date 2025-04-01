# Upload File

Upload File is a command-line tool to upload files and folders to different online file hosts.

It is used in [an Alfred Workflow of the same name](https://alfred.app/workflows/vitor/upload-file/).

## Installation

Install with [Homebrew](https://brew.sh):

```shell
brew install vitorgalvao/tiny-scripts/upload-file
```

Alternatively, download the executable at the root of this repository and call it directly.

## Usage

```
Upload files and directories to a file hosting service.
If multiple files or a directory are given, they will be zipped beforehand.
To set a host as the default, export UPLOAD_FILE_TO in your shell.

Valid hosts:
  
  0x0.st
  litterbox.catbox.moe
  transfer.archivete.am
  filebin.net
  oshi.at

Usage:
  upload-file [options] <path...>

Options:
  -u, --upload-host <host>   File host to upload to. Defaults to 0x0.st.
  -d, --dummy-text <text>    Does nothing but provides an anchor to detect execution from other processes.
  -h, --help                 Show this help.
```

## License

3-Clause BSD
