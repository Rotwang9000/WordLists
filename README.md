# WordLists

Alternative BIP39 wordlists for mnemonic seed phrases. Each wordlist contains exactly 2048 words as required by the BIP39 standard.

## Wordlists

### `swearwords.txt`
A list of 2048 swearwords and profanities, including variations, compounds, and regional terms. Contains strong language.

### `polari.txt`
A Polari wordlist. Polari is a historical British slang/cant language. Due to the limited authentic Polari vocabulary, this list includes made-up words following Polari linguistic patterns (backslang, rhyming slang, Italianate endings).

### `esperanto.txt`
A list of 2048 Esperanto base words (no inflected variants). The vocabulary is drawn from the entries of the Esperanto–English dictionary at Esperanto Panorama.[^1]

### `elder_futhark.txt`
An Elder Futhark/Old Norse wordlist. Contains the 24 Elder Futhark rune names and Old Norse words (transliterated to Latin alphabet), including vocabulary related to mythology, warriors, nature, and daily life.

### `elder_futhark_runes.txt`
An Elder Futhark wordlist using actual Unicode rune characters (ᚠᚢᚦ...). Contains combinations of runes and rune sequences, providing an authentic runic representation.

### `emoji.txt`
An emoji wordlist containing 2048 unique emojis from various categories (faces, animals, food, objects, symbols, etc.). Each "word" is a single emoji character.

### `reverse_order_english.txt`
The standard BIP39 English wordlist with the order reversed (last word becomes first, etc.). This creates an obfuscated wordlist that looks like a normal phrase but uses different word positions.

### `reversed_spelling_english.txt`
The standard BIP39 English wordlist with each word's spelling reversed (e.g., "abandon" becomes "nodnaba"). This creates an obfuscated wordlist while maintaining the same structure as the original.

## Usage

These wordlists are provided as separate text files, one word per line. They can be used with BIP39-compatible wallet software that supports custom wordlists.

### Online Converter

A web-based converter is available at `index.html` (for GitHub Pages). It allows you to convert mnemonic phrases between different wordlists. The converter runs entirely client-side - your phrases never leave your browser.

**Note:** These are alternative wordlists for novelty or obscurity purposes. The standard BIP39 English wordlist remains the most widely supported and tested option for production use.

[^1]: Esperanto Panorama dictionary, <https://esperanto-panorama.net/vortaro/eoen.htm>.