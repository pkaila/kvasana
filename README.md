# Kvasana (Quordlen suomenkielinen version)

Testaa taitosi ja ratkaise 4 Wordleä samaan aikaan! Käytössäsi on 9 arvausta kaikkien neljän sanan arvaamiseksi. Uusi Kvasana tulee ratkaistavaksi joka päivä.

 * Pelaa peliä osoitteessa <a href="https://kvasana.fugu.iki.fi">https://kvasana.fugu.iki.fi</a>
 * Alkuperäinen englannin kielinen versio löytyy osoitteesta <a href="www.quordle.com">www.quordle.com</a>

How to translate to your language:
1. In index.html, change the locale in the HTML tag.
2. Translate the index.html file manually.
3. Duplicate the "en.js" in assets/lang and rename it to your locale name (ie. fi.js for Finnish).
4. In assets/index.js on line 64, change the path to the locale file according to your language.
  * If you need to support additional letters modify the `Ne` variable.
  * Change the locale for the "RelativeTimeFormat"
5. Fully translate the locale file. 
  * Be careful with the "rules" variable and keep the HTML structure.
  * You can put in wordPick the list of words that can be used by the script to be played.
  * You can put in wordList the list of words that will be accepted as guesses.
  * If you need a different keyboard layout modify the `keyboardLayout*` variables.
6. Upload, you're done!
