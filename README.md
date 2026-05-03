# REAPER Project File Syntax — VSCode Extension

Syntax highlighting for [REAPER](https://www.reaper.fm/) project files (`.rpp`, `.rpp-bak`).

## Features

| Token | Example | Scope |
|---|---|---|
| **Tags** | `<PROJECT`, `<TRACK` | `entity.name.tag.rpp` |
| **Properties** | `NAME`, `VOLPAN`, `SEL` | `keyword.other.property.rpp` |
| **Double-quoted strings** | `"My Track"` | `string.quoted.double.rpp` |
| **Single-quoted strings** | `'value'` | `string.quoted.single.rpp` |
| **Backtick strings** | `` `value` `` | `string.quoted.other.backtick.rpp` |
| **GUIDs** | `{A1B2C3D4-1234-...}` | `constant.other.guid.rpp` |
| **Floats** | `0.75`, `-3.14` | `constant.numeric.float.rpp` |
| **Integers** | `1`, `-42` | `constant.numeric.integer.rpp` |
| **Base64 blobs** | `SGVsbG8=` | `string.unquoted.base64.rpp` |
| **Comments** | `// note` | `comment.line.double-slash.rpp` |

### Code folding
Blocks delimited by `<TAG … >` fold automatically.

### Bracket/quote auto-close
`"`, `'`, `` ` ``, and `{` auto-close when typed.

## Supported file extensions

`.rpp` · `.RPP` · `.rpp-bak` · `.RPP-BAK`

## License

MIT
