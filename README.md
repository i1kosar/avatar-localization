# Avatar Sorani v5

Resource host for the finished Sorani Kurdish localization and Android download-and-launch pipeline.

The verified PS2 image is **Avatar: Into the Inferno**, disc ID `SLUS_218.04`. Its existing fonts, RTL shaping, wrapping, and punctuation fixes are included in the v5 image.

## Release v5

Attach these four files to the GitHub release tagged `v5`, preserving their names:

- `Avatar_Kurdish_Sorani_NRT_v5.iso.part001`
- `Avatar_Kurdish_Sorani_NRT_v5.iso.part002`
- `Avatar_Kurdish_Sorani_NRT_v5.iso.part003`
- `avatar-v5-parts.json`

The manifest records the ordered part sizes and SHA-256 checksums. The reconstructed ISO is 2,828,507,136 bytes and has SHA-256:

```text
d482ada7da7b81890c008c9bdcdfd2d774eb0981152e366070009a26378fa0b5
```

The Android launcher verifies the downloaded image and opens it in a separately installed PS2 emulator such as Play!. Configure GitHub credentials privately in the downloader or app; keep tokens and signing keys out of repository files.
