# Ergonomic QWERTY-ish Arabic Keyboard Layout

I'm learning Levantine Arabic and I wanted to learn to type without having to
learn an entire new keyboard layout.

There are some other QWERTY-ish layouts out there, but none of them had
everything that I wanted so I designed this one.

I don't know if this will be useful to anyone else, but I thought I would share
it in case it is.

# Installation on Windows
Use [Microsoft Keyboard Layout Creator][KLC] to compile `arabic-ng.klc` into a
setup program and run that.

[KLC]: https://www.microsoft.com/en-us/download/details.aspx?id=102134

# Installation on Mac
Copy `Arabic - NG.bundle` to `~/Library/Keyboard Layouts`

To edit the layout, you can use [Ukelele].

[Ukelele]: https://software.sil.org/ukelele/

# "Easy" letters

When there is a direct enough correspondence between Latin and Arabic letters,
the corresponding QWERTY key is used to the matching Arabic letter. These should
be obvious with the possible exception of the ones that have a note attached.

| Arabic  | QWERTY | Unicode Name       | Note  |
|--------:|--------|--------------------|-------|
| ا       | `a`    | ARABIC LETTER ALEF |       |
| ب       | `b`    | ARABIC LETTER BEH  |       |
| ت       | `t`    | ARABIC LETTER TEH  |       |
| ج       | `j`    | ARABIC LETTER JEEM |       |
| د       | `d`    | ARABIC LETTER DAL  |       |
| ر       | `r`    | ARABIC LETTER REH  |       |
| ز       | `z`    | ARABIC LETTER ZAIN |       |
| س       | `s`    | ARABIC LETTER SEEN |       |
| ف       | `f`    | ARABIC LETTER FEH  |       |
| ق       | `q`    | ARABIC LETTER QAF  |       |
| ك       | `k`    | ARABIC LETTER KAF  |       |
| ل       | `l`    | ARABIC LETTER LAM  |       |
| م       | `m`    | ARABIC LETTER MEEM |       |
| ن       | `n`    | ARABIC LETTER NOON |       |
| ه       | `h`    | ARABIC LETTER HEH  |       |
| و       | `u`    | ARABIC LETTER WAW  | (1)   |
| ي       | `i`    | ARABIC LETTER YEH  | (1)   |
| پ       | `p`    | ARABIC LETTER PEH  | (2)   |
| گ       | `g`    | ARABIC LETTER GAF  | (2)   |
| ڤ       | `v`    | ARABIC LETTER VEH  | (2)   |

## Notes

1. I also considered `w` for `و` and `y` for `ي`, but after some
   experimentation, `u` and `i` felt more natural and comfortable.
2. Additional letters sometimes used to express foreign `g`, `p`, and `v` sounds

# Emphatic consonants

`;` dead key is used in combination with corresponding Latin letter.

| Arabic  | QWERTY | Unicode Name      |
|--------:|--------|-------------------|
| ص       | ‎`;s`   | ARABIC LETTER SAD |
| ض       | ‎`;d`   | ARABIC LETTER DAD |
| ط       | ‎`;t`   | ARABIC LETTER TAH |
| ظ       | ‎`;z`   | ARABIC LETTER ZAH |

# "Difficult" letters

Digits are used as in Arabizi.

| Arabic  | QWERTY | Unicode Name        |
|--------:|--------|---------------------|
| ع       | ‎`3`    | ARABIC LETTER AIN   |
| خ       | ‎`5`    | ARABIC LETTER KHAH  |
| ح       | ‎`7`    | ARABIC LETTER HAH   |
| غ       | ‎`8`    | ARABIC LETTER GHAIN |

# Hamza and Madda

For hamza on the line, `2` is used as in Arabizi. For hamza above, `'` dead key
is used in combination with the key for the hamza seat. `e` alone is used for
alef with hamza below and `'` dead key applied to `e` gives alef madda.

| Arabic  | QWERTY | Unicode Name                         |
|--------:|--------|--------------------------------------|
| ء       | ‎`2`    | ARABIC LETTER HAMZA |
| أ       | ‎`'a`   | ARABIC LETTER ALEF WITH HAMZA ABOVE  |
| إ       | ‎`e`    | ARABIC LETTER ALEF WITH HAMZA BELOW  |
| آ       | ‎`'e`   | ARABIC LETTER ALEF WITH MADDA ABOVE  |
| ؤ       | ‎`'u`   | ARABIC LETTER WAW WITH HAMZA ABOVE   |
| ئ       | ‎`'i`   | ARABIC LETTER YEH WITH HAMZA ABOVE   |

# Remaining letters

The remaining arabic letters are mapped to the remaining QWERTY keys.

| Arabic  | QWERTY | Unicode Name               | Rationale                    |
|--------:|--------|----------------------------| -----------------------------|
| ى       | `y`    | ARABIC LETTER ALEF MAKSURA | Looks like a dotless **y**aa |
| ة       | `o`    | ARABIC LETTER TEH MARBUTA  | Looks like an o with dots    |
| ش       | `c`    | ARABIC LETTER SHEEN        | C as in ch in French         |
| ث       | `w`    | ARABIC LETTER THEH         | Arbitrary                    | 
| ذ       | `x`    | ARABIC LETTER THAL         | Arbitrary                    |

# Numbers

Since we use numbers for the difficult letters, we need another way to type
numbers. The top row of the QWERTY letters is used with the shift modifier.

| Arabic  | QWERTY     | Unicode Name             |
|--------:|------------|--------------------------|
| ١       | `shift+q`  | ARABIC-INDIC DIGIT ONE   |
| ٢       | `shift+w`  | ARABIC-INDIC DIGIT TWO   |
| ٣       | `shift+e`  | ARABIC-INDIC DIGIT THREE |
| ٤       | `shift+r`  | ARABIC-INDIC DIGIT FOUR  |
| ٥       | `shift+t`  | ARABIC-INDIC DIGIT FIVE  |
| ٦       | `shift+y`  | ARABIC-INDIC DIGIT SIX   |
| ٧       | `shift+u`  | ARABIC-INDIC DIGIT SEVEN |
| ٨       | `shift+i`  | ARABIC-INDIC DIGIT EIGHT |
| ٩       | `shift+o`  | ARABIC-INDIC DIGIT NINE  |
| ٠       | `shift+p`  | ARABIC-INDIC DIGIT ZERO  |

Western Arabic numerals can be typed using Right Alt (AltGr)/Option and QWERTY number keys.

# Punctuation

Punctuation is in the same place as QWERTY, but Arabic equivalents are used when
applicable. In those cases, ASCII equivalent can be typed using Right Alt
(AltGr) / Options. 

Additional Arabic punctuation is accessed with shift and home row keys. 

Use corresponding dead key with space to produce ASCII `;` or `'`.

There seems to be a limitation on Windows or [KLC] that prevents dead keys from
having non-ASCII characters, so Arabic semicolon is moved to `shift+l`.

| Arabic  | QWERTY     | Unicode Name               |
|--------:|------------|----------------------------|
| ،       | `,`        | ARABIC COMMA               |
| ؟       | `?`        | ARABIC QUESTION MARK       |
| ٪       | `%`        | ARABIC PERCENT SIGN        |
| _       | `_`        | ARABIC TATWEEL             |
| ؛       | `shift+l`  | ARABIC SEMICOLON           |
| ٫       | `shift+k`  | ARABIC DECIMAL SEPARATOR   |
| ٬       | `shift+j`  | ARABIC THOUSANDS SEPARATOR |

| ASCII  | QWERTY    | UNICODE NAME   | AKA        |
|-------:|-----------|----------------|------------|
| `,`    | `alt+,`   | COMMA          |            |
| `?`    | `alt+?`   | QUESTION MARK  |            |
| `%`    | `alt+%`   | PERCENT SIGN   |            |
| `_`    | `alt+_`   | LOW LINE       | UNDERSCORE |
| `;`    | `; `      | SEMICOLON      |            |
| `'`    | `' `      | APOSTROPHE     |            |

# Tashkeel

`;` dead key is used in combination with is used in combination with a
corresponding Latin letter.

| Arabic | QWERTY | Unicode Name    | Rationale    |
|-------:|--------|-----------------|--------------|
| ـَ      | `;a`   | ARABIC FATHA    | Phonetic     |
| ـُ      | `;u`   | ARABIC DAMMA    | Phonetic     |
| ـِ      | `;e`   | ARABIC KASRA    | Phonetic     |
| ـّ      | `;w`   | ARABIC SHADDA   | Shape        |
| ـْ      | `;o`   | ARABIC SUKUN    | Shape        |
| ـً      | `;n`   | ARABIC FATHATAN | Phonetic     |
| ـٌ      | `;m`   | ARABIC DAMMATAN | Da**mm**atan |
| ـٍ      | `;k`   | ARABIC KASRATAN | **K**asratan |

# Examples

Here are some examples. Notice how the QWERTY input ends up being somewhat
readable.

| Arabic | QWERTY   |
| ------:|----------|
| مرحبا  | ‎`mr7ba`  |
| عربي   | ‎`3rbi`   |
| كيفَك   | ‎`kif;ak` |  
| شكراً   | ‎`ckra;n` |
| حمص    | ‎`7m;s`   |
| تبولة  | ‎`tbulo`  |
