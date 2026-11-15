# CLAUDE.md

Batch image compressor using the tinify.com (TinyPNG) API. Fork of upstream ameer1234567890/tinifier; remote `andrius/tinifier`.

- Base: `alpine`; ships `tinifier.sh`, volumes `files/` (input) and `compressed/` (output).
- Needs `.tinify_api_key` mounted; build `docker build -t tinifier .`, then run mounting the key + folders (see README).
- Last commit: 2018-12-26.
