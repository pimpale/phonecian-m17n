# Phonecian / Paleo-Hebrew m17n module

This is a [m17n](https://www.nongnu.org/m17n/) module for the Phonecian script.

The Phonecian script is the ancestor of the:
* Latin script
* Greek script
* Cryllic script
* Hebrew script
* Arabic script
* ... and many more!

In its heyday, the script was used for Phonecian, Paleo-Hebrew, Punic, and other ancient northwestern Semitic languages.

Unicode assigned all of them the same script block, [Phonecian](https://en.wikipedia.org/wiki/Phoenician_(Unicode_block)) (U+10900..U+1091F).

## Assignments:

| Input | Letter | Unicode | Code Point | Notes |
|-------|--------|---------|------------|-------|
| `'` | ALF | 𐤀 | U+10900 | Often denoted ʾ in academic literature, mapped to `'` since `'` is commonly used to represent glottal stops. |
| `b` | BET | 𐤁 | U+10901 | |
| `g` | GAML | 𐤂 | U+10902 | |
| `d` | DELT | 𐤃 | U+10903 | |
| `h` | HE | 𐤄 | U+10904 | |
| `w` | WAU | 𐤅 | U+10905 | |
| `z` | ZAYIN | 𐤆 | U+10906 | |
| `.h` | HET | 𐤇 | U+10907 | Often denoted ḥ in academic literature |
| `.t` | TET | 𐤈 | U+10908 | Often denoted ṭ in academic literature |
| `y` | YOD | 𐤉 | U+10909 | |
| `k` | KAF | 𐤊 | U+1090A | |
| `l` | LAMD | 𐤋 | U+1090B | |
| `m` | MEM | 𐤌 | U+1090C | |
| `n` | NUN | 𐤍 | U+1090D | |
| `s'` | SEMK | 𐤎 | U+1090E | Often denoted ś in academic literature |
| `.'` | AIN | 𐤏 | U+1090F | Often denoted ʿ (n.b: this is the reverse of ʾ) in academic literature, mapped somewhat arbitrarily to `.'` since it's related to `ʾ`, and appears less frequently than it. |
| `p` | PE | 𐤐 | U+10910 | |
| `.s` | SADE | 𐤑 | U+10911 | |
| `q` | QOF | 𐤒 | U+10912 | |
| `r` | ROSH | 𐤓 | U+10913 | |
| `sh` | SHIN | 𐤔 | U+10914 | Often denoted š in academic literature |
| `t` | TAW | 𐤕 | U+10915 | |
| `\|` | Word separator | 𐤟 | U+1091F | |

### Escapes

| Input | Output |
|-------|--------|
| `''` | `'` |
| `..` | `.` |
| `\|\|` | `\|` |
