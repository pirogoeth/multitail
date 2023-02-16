# multitail

Tail file(s) from multiple remote hosts all at once.

## Installation

_Should_ be as simple as `poetry install` within the repository. 

## Usage

```
Usage: multitail [OPTIONS]

Options:
  -H, --host TEXT                 Hostname to tail on, can be specified
                                  multiple times
  --hosts-stdin / --no-hosts-stdin
                                  Read a list of newline-delimited hosts from
                                  stdin
  -p, --path TEXT                 Path to tail  [required]
  --seek-offset INTEGER           Byte offset to seek in the file
  --seek-whence [SEEK_SET|SEEK_END]
  --sudo-as TEXT                  User to sudo to for reading
  --debug / --no-debug            Whether debug logging should be turned on
  --help                          Show this message and exit.
```

## Limitations

- [ ] Currently only tails a single file from multiple hosts.
