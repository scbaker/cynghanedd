# Cynghanedd Solver

## What is cynghanedd?

Cynghanedd (kəŋˈhaneð), literally "chiming" or "harmony," is a core concept of Welsh poetry. 

The word refers to the "patterning of consonants, accents, and rhyme" within lines of a poem (Lewis). Cynghanedd is every bit as complicated as it sounds--especially in English, which follows very different morphological rules than Welsh.

Wikipedia has [a basic description of the various forms of cynghanedd](https://en.wikipedia.org/wiki/Cynghanedd). Gwyneth Lewis has also [written about the concept for _Poetry_ Magazine](https://www.poetryfoundation.org/poetrymagazine/articles/70172/extreme-welsh-meter). For a more detailed discussion in English, see [_Gwenllian's Poetry Primer_ by Katherine L. Bryant](https://web.archive.org/web/20050308123639/http://home.comcast.net/~bryant.katherine/primer.html) and [Mererid Hopwood's _Singing in Chains: Listening to Welsh Verse_](https://wou.on.worldcat.org/search?queryString=no:56912518&databaseList=638#/oclc/56912518). 

## What does this solver do?

At the moment, nothing!

Once completed, it will initially allow the user to enter a word or words and search for correspondences among other words. Accent and rhyme may be added later depending on the availability of open datasets.

## How will it work?

Regular expressions, MySQL, and PHP.

## What does this solver not do?

It won't write poems for you. Or at least, not good ones.

## Where do the words come from?

The solver uses Kevin Atkinson's [SCOWL (Spell Checking Oriented Word Lists)](http://wordlist.aspell.net/scowl-readme/) to find matches for entered words.
