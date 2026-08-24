# OverTheWire / Bandit - Levels 0 to 14 summary

## Objective:
Build practical Linux command-line experience through OverTheWire's Bandit wargame, a series of SSH-based Linux puzzles where each challenge's solution provides a password to log into the next level.

### Environment
- Kali Linux

### Steps Performed
worked through Bandit Levels 0 through 14 via **SSH**, covering fundamentals:

1. Basic Linux file navigation:

`ls -la`
`cat`
`file`
`hidden files`
`files with spaces`

2. Searching and filtering and ownership:
`grep`
`find`
`find -user {name} -group {name}`
`sort {filename} | uniq -u`  uniq: it filters the file and only outputs identical lines; -u: it outputs only lines that appear once.

3. Data extraction:
`strings {filename}`: it finds printable characters; it handels dump/hex/excutable files.
`base64 -d`: it's mainly an encoding technique (in base64 scheme), and with -d it can decode files which use this scheme.
`cat {filename} | tr 'old pattern' 'new pattern'`: tr allows replacing characters with others.





