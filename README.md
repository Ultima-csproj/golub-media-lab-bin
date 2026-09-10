# golub-media-lab-bin

Public distribution repository for MediaLab parser binaries.

The source code is kept private in
[`Ultima-csproj/golub-media-lab`](https://github.com/Ultima-csproj/golub-media-lab).
This repository intentionally contains no parser source. Each versioned GitHub
Release contains:

- `media_lab_parser_fast-windows-x64.exe`
- `media_lab_parser_fast-linux-x64`
- `SHA256SUMS`

The launchers in `golub_mobile` download a pinned release and verify its
SHA-256 checksum before executing it. Releases are immutable distribution
points; binaries are not taken from the `main` branch.
Public MediaLab parser binaries and checksums
