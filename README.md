### QWERTY-based keyboard layout for Ubuntu

The original Esperanto keyboard layout for Ubuntu works well, but it makes characters with diacritics replace the standard latin characters which aren't used in Esperanto (like q or w).

It makes it hard to quickly switch between Esperanto and English language. I have to do it when I solve the quiz on [Duolingo](https://duolingo.com). That's why I've modified the keyboard setting to incorporate esperanto keys into the basic US keyboard layout.

Characters with diacritics are obtained by pressing the key while holding altGr (right alt):

```
ŭ = alt + u
ŝ = alt + s
ĝ = alt + g
ĥ = alt + h
ĵ = alt + j
ĉ = alt + c
```

### How to setup

To make it work, it's necessary to paste the `epo` file into `/usr/share/X11/xkb/symbols/` directory.
I suggest to make a backup of the original `epo` just in case.

It may work for the other Linux distributions, but location of the keyboard layouts directory may be different.

