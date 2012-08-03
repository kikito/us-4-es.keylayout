# us-4-es.keylayout

A mac US-based keyboard layout thought for people who have to write Spanish characters from time to time

# Explanation

This keyboard layout for mac moves/changes some of the "option" key modifiers so they are more useful to people who have to switch between
English and Spanish on their day-to-day job using mac.

In other words, this layout makes easier to write the characters on this list: ¡¿áéíóúüÁÉÍÓÚÜñÑ


    Glyph   Us Layout   us-4-es layout   us-4-es  alt
    -------------------------------------------------
      á       ⌥ e, a         ⌥ a            ⌥ ', a
      é       ⌥ e, e         ⌥ e            ⌥ ', e
      í       ⌥ e, i         ⌥ i            ⌥ ', i
      ó       ⌥ e, o         ⌥ o            ⌥ ', o
      ú       ⌥ e, u         ⌥ u            ⌥ ', u
      Á       ⌥ e, ⇧ a       ⌥ ⇧ a          ⌥ ', ⇧ a
      É       ⌥ e, ⇧ e       ⌥ ⇧ e          ⌥ ', ⇧ e
      Í       ⌥ e, ⇧ i       ⌥ ⇧ i          ⌥ ', ⇧ i
      Ó       ⌥ e, ⇧ o       ⌥ ⇧ o          ⌥ ', ⇧ o
      Ú       ⌥ e, ⇧ u       ⌥ ⇧ u          ⌥ ', ⇧ u
      ñ       ⌥ n, n         ⌥ n
      Ñ       ⌥ n, ⇧ n       ⌥ ⇧ n
      ü       ⌥ u, u         ⌥ ⇧ ', u
      Ü       ⌥ u, ⇧ u       ⌥ ⇧ ', ⇧ u
      ¿       ⌥ ⇧ /          ⌥ /
      ¡       ⌥ 1            ⌥ 1

Notes:

* Accented vowels are accesible via ⌥  + vowel / uppercase vowel.
* On the ES layout, accent is on the ' key. That's why I've included an "alternative" way to type the words, using ⌥ ' and then the vowel. This makes the ' key behave like
  on the ES layout, except that you need to remember to press ⌥ before the accent.
* The ~ accent is not possible to produce. Istead, ñ and Ñ are produced directly with ⌥ n and ⌥ N.
* The ¨ accent has been moved to ⌥ ⇧ '. This makes tying ü and Ü a bit more complex, but simplifies the much common case (ú and Ú).
* The opening exclamation mark makes a lot of sense on the US layout, so I have not modified it on this layout. I wanted to include it on the list above for completeness.

# Installation

1. Download the us-4-es.keylayout file from this repository
2. Copy it to ~/Library/Keyboard Layouts (Remember that ~/Library migth be hidden)
3. Go to System Preferences/Language & Text/Input Sources and activate us-4-es (you might need to scroll quite a bit to find it on the list)
4. Make sure "Show input menu in menu bar" is activated
5. A flag representing your current keyboard layout should have appeared in the menu bar, near the top right. Click on it, and you should see us-4-es in the menu that will appear.
6. You can use us-4-es now

# Credits

The .keylayout format is xml-based, and a bit of a pain to work with via a text editor. Instead of using vim to create this layout, I used a tiny app called
[ukeleke](http://scripts.sil.org/ukelele). It provides a more human-friendly way to create keyboard layouts, and I definitively recommend it (just remember that
"Dead keys" means "accent keys"). Give it a look if you want to do a uk-4-es layout, for example.

