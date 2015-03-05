# note <|note>

Use this command to set or update a device note.

If note command isn't passed, the tool attempts to read from `stdin`.

To view the notes, use $ resin device <id>.

Examples:

	$ resin note "My useful note" --device 317
	$ cat note.txt | resin note --device 317

## Options

### --device, --d,dev, --d,dev <device>

device id