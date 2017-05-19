rot

Apply rotational 13 cypher to hide text.

# Usage:

`rot [FILE …]`

If no file is passed, uses stdin.

Note: this cypher is not suitable for encryption. It can be useful to prevent
accidental reading of the encrypted content – e.g., to hide spoilers on social
media in such a way that people can read it if they want, but have to take an
explicit step to do so.

An interesting property of rotational 13 cypher is that it is its own reverse.
In other words: `rot | rot` is identical to `cat`.
