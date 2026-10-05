# Snova IO (`Snova.Std.IO`)

Standard Input and Output library written in 100% pure Snovalang.

## Features
- `Reader`, `Writer`, `Closer` stream interfaces
- `ByteBuffer` in-memory dynamic buffer
- `copy` stream piping and chunked data transfer

## Documentation Example
```snl
/* -- Doc:{copy}
 *
 * -- Description: Copies all data from a Reader into a Writer until EOF is reached.
 *
 * -- Param{src}: Source readable stream.
 * -- Param{dst}: Destination writable stream.
 * -- Param{bufferSize}: Size of the temporary chunk buffer.
 * -- Returns: Total number of bytes copied.
 */
```

## License

This project is licensed under the [Apache License, Version 2.0](LICENSE).
Copyright 2026 Snovalang contributors. See [NOTICE](NOTICE).
