# rod-ext-procwatch

procwatch -- Resident process-create telemetry: a compiled-in watch samples the process table on a fixed cadence and buffers creation rows, and recon.procwatch flushes the rows since the last ask -- the implant-native tier's first real entry.

A Rod capability module (entry kind: extension) in the
[Rod](https://github.com/rodframework/Rod) ecosystem: the Rust sources
under `src/` compile into implant builds through the rod-rust build
unit's extension overlay. The manifest (`rod-module.toml`) is the
contract; the package installs from the
[rod-registry](https://github.com/rodframework/rod-registry) index:

    rod mod install procwatch

## License

Apache-2.0, as declared in the manifest.
