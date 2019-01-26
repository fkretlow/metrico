## Metrico

### Compatibility
Metrico makes use of combined OpenType features in a somewhat unorthodox way. Theoretically the font _should_ work in any modern application that supports the LIGA, CALT and KERN features.

**Dorico:** Metrico works perfectly with Dorico on Windows.  
Due to [a bug in the Qt framework](https://bugreports.qt.io/browse/QTBUG-69803) that Dorico is built upon the font does only partly work in Dorico on Mac. Basic figures and swing indications should work, everything else that involves vertical placement of tuplet numbers will currently not work.

**Finale:** Finale’s OpenType support is frustratingly erratic. There’s no guarantee that your particular metric equation will work as expected...

**Sibelius:** Not tested. I expect Metrico to work fine with Sibelius 2018.11 or greater.