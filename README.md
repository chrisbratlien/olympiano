#### Overview

Olympiano will keep generating a continuous degree/chord progression and then rotate in improv lambdas at each chord to play their
own interpretation of the chord.  These lambdas may be as laid back as :george, who just holds down all the notes in a chord, to the frantic
arpeggios of :hammett.  Then there's :inward_a who sort of plays spin-the-bottle with the chords he's given to play.  :peggy plays the straight
up-and-down arpeggio.

I'm using some programming paradigms found in Archaeopteryx.  Many thanks to Giles Bowkett for his brilliant project.

Olympiano doesn't have a strong enough concept of rhythm and tempo to enforce beats and measures.  Different improv lambdas
have permission to hog the spotlight for as long as they wish.  That has pros and cons.  For that reason I think it's more 
suited for generating that soothing background classical piano sound.  But I could be wrong.


#### Dependencies

- [chrisbratlien/rb-music-theory](https://github.com/chrisbratlien/rb-music-theory)
- [arirusso/micromidi](https://github.com/arirusso/micromidi)

#### Installation

First, grab rb-music-theory

```bash
git clone git://github.com/chrisbratlien/rb-music-theory.git 
cd rb-music-theory
gem install rb-music-theory --user-install
gem install micromidi --user-install
```



#### Running Olympiano
```bash
cd olympiano
ruby launcher.rb
```