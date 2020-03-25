# rime-kana_zaonhegho

Refer to the PDF document `KanaZaonhe.pdf` for details of this orthography.

Because Shanghainese employs a wider set of phonemes than that Kana is designed for, some extensions to Kana are used.

- combinations of glyphs of fairly common code points supported by most fonts (e.g. サ゚). This WILL be rendered correctly with the `ccmp` feature turned on with most Japanese `Pro(N)` fonts.
- however some other are not included in most fonts (e.g. small katakana we `U+1B165`).

**Two strategies provided to display all glyphs used**:

- use the font provided (`Zaonhe-CL-Light-subset.ttf`), which is an extension of [Genyog](https://github.com/ButTaiwan/genyog-font), an open source font based on Source Han Sans. Currently I've only created a Light weight for my personal use on [Nyoeghau.com](https://www.nyoeghau.com/).
  - *Digression*: Several common Shanghainese/Wu ideographs are appended as well. The complete list: `U+2BE3B` ⿰弗要, `U+277F0` ⿰勿要, `U+23350` ⿰勿會, `U+20C8E` ⿰口伐. I recommend inputting them with my [Shanghainese Input Method (README in Mandarin)](https://github.com/edward-martyr/rime-yahwe_zaonhe). This production of this schema itself involved my [hentaigana input method (README in English)](https://github.com/edward-martyr/rime-hentaigana).
- use the `opencc` feature (already integrated. find it under menu) which by default converts small we, wo, nn to small e, o and large nn.

I'll add to README when I'm freer next week.
