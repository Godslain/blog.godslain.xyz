---
layout: post
title: "The Runic Script"
date: 2025-04-07 00:00:00 +0100
author: demecate
type: devblog
---

<style>
@font-face {
  font-family: 'RunicScript';
  src: url('../assets/fonts/Godslain-ancient-runic.ttf') format('truetype');
  /* Alternative remote source:
  src: url('https://runes.godslain.xyz/fonts/Godslain-ancient-runic.ttf') format('truetype');
  */
}

.runes {
  font-family: 'RunicScript', sans-serif;
  font-size: 500%;
  text-align: center;
  display: block;
}
</style>


# The Forgotten Scripture

## Table 1: Letters and Runes

| Letter | Example     | Notes                                                                                                                                         | Runes |
|--------|-------------|-----------------------------------------------------------------------------------------------------------------------------------------------|-------|
| 0      | Sa’en       | (Unused) Two syllables with a glottal stop. All other runes derive from this one. | <span class="runes">a</span>  |   
| 1      | A, a        | Athnod (..)<br>The 'a' in 'father' or 'car'.<br>Open back unrounded vowel [ɑ]. |<span class="runes">b</span>                                                      |                                                   
|2      | ae          | Aedir (...)<br>Pronounced as "a" followed by "e" in two distinct syllables.<br>Diphthong or hiatus [a.e], depending on speaker articulation. | <span class="runes">Æ</span> |
| 3      | B, b        | The b in brown.<br>Voiced bilabial stop [b].                                                                                                 |<span class="runes">b</span> |
| 5      | D, d        | The d in death.<br>voiced dental stop [d]. |  <span class="runes">d</span> |
| 6      | E, e        | Enathra (...)<br>The e in bet or pen.<br>Open-mid front unrounded vowel [ɛ]. |<span class="runes">e</span>     |
| 7      | F, f        | Efar (..)<br>The f in fellow.<br>Voiceless labiodental fricative [f].                                                                        |     <span class="runes">f</span>   |
| 8      | G, g        | Gaenthor (_.)<br>The g in garment.<br>Voiced velar plosive [ɡ].                                                                              |   <span class="runes">g</span>     |
| 9      | G̊, g̊       | G̊ammos (..)<br>The g̊ is pronounced by rolling the epiglottis.<br>Voiced epiglottal trill [ʢ].                                              | <span class="runes">7</span>       |
| 10     | H, h        | Huunn (_)<br>The h in horrendous. Voiceless glottal fricative [h].                                                                           |    <span class="runes">h</span>   |
| 11     | hh          | HHarduk (..)<br>Voiceless radical pharyngeal non-sibilant fricative [ħ]. | <span class="runes">Ĥ</span> |
 | 12     | HR, hr      | Hrann (.)<br>The h in Hriannon(Welsh). Voiceless glottal fricative [h].                                                                      |     <span class="runes">8</span>  |
| 13     | İ, i        | Kharthìr (._)<br>The i in think. Voiceless dental fricative [θ]. In this example, the ì is also stressed.                                   |   <span class="runes">I</span>    |
| 14     | ei          | Gheima (_.)<br>Diphthong [eɪ], similar to "rein," "vein," or "sane". With glottal stop: Einar vs E'inar.                                     |  <span class="runes">5</span>     |
| 15     | ai          | Naira (_.)<br>Diphthong [aɪ], similar to "ride." With glottal stop: Naira vs Na'ira.                                                         |    <span class="runes">1</span>   |
| 16     | J, j        | (rune)<br>[ʒ] like "measure" or [ʃ] as in “shoe” (by common folk).                                                                            |    <span class="runes">j</span>   |
| 17     | k           | Kelleth (..)<br>“c” in “cat”. Voiceless velar plosive [k].                                                                                   |  <span class="runes">k</span>    |
| 18     | kh          | Khayldyn (._.)<br>Always the c in “card”. Voiceless velar plosive[k].<br>[kaːr] vs [kæːr]                                                    | <span class="runes">;</span>      |
| 19     | L, l        | Laenu (_.)<br>"l" in "lake" (soft) or "lard" (hard). Voiced alveolar lateral approximant [l].                                                | <span class="runes">l</span>      |
| 20     | lh          | Lhâradon (_..)<br>Hard “l,” like in "lament".<br>[l'ha.ra] vs []                                                                             |   <span class="runes"></span>    |
| 21     | M, m        | The m in moral.<br>Voiced bilabial nasal [m].                                                                                                |   <span class="runes">m</span>    |
| 22     | n           | Noolenoei (_.._)<br>The n in name. Hard n by default.                                                                                        |     <span class="runes">n</span>  |
| 23     | nh          | Nhâden (_.)<br>Always the hard “n” in “note”.                                                                                                |    <span class="runes">></span>   |
| 24     | nâ          | Puunâr (_ _)<br>N with a long a. Becomes "ny" sound. Predorsal nasal [n̺].     | <span class="runes">ñ</span>    |
| 25     | ŋ, ɲ        | Eɲgol (..)<br>The ng sound in song or long. Velar nasal [ŋ].                                                                                 |    <span class="runes">ŋ</span>  |
| 26     | O, o        | Oruudun (._.)<br>The o in home. Mid back rounded vowel [o].                                                                                  |     <span class="runes">o</span>  |
| 27     | P           | The p in pat.<br>Voiceless bilabial stop [p].                                                                                                |   <span class="runes">p</span>    |
| 28     | R, r        | Ŕuai (_.)<br>The r in caro. Apical alveolar tap [ɾ].                                                                                         |     <span class="runes">r</span>  |
| 29     | R̊, r̊       | Er̊uk (..)<br>The r in río. Apical alveolar trill [r].                                                                                       |     <span class="runes">2</span>  |
| 30     | S, s        | The s in sun.<br>Voiceless alveolar fricative [s].                                                                                           |    <span class="runes">s</span>   |
| 31     | T, t        | The t in top.<br>Voiceless alveolar stop [t].                                                                                                |    <span class="runes">t</span>   |
| 32     | dh          | İdhis (..)<br>Same sound as "th" in then. Voiced dental fricative [ð].                                                                       |     <span class="runes">4</span>   |
| 33     | th          | Kelleth (..)<br>The th in think. Voiceless dental fricative [θ].                                                                             |     <span class="runes">3</span>  |
| 34     | û Û U       | Unûldun (._.)<br>The long u in rule. Long close back rounded vowel [uː].                                                                     |    <span class="runes">u</span>   |
| 35     | I, ı        | Sı’ıgta (…)<br>The ı in kırmızı. Close back unrounded vowel [ɯ].                                                                             |     <span class="runes">ı</span>  |
| 36     | Ü, ü        | Ÿrdÿn (..)<br>The ü in über. Close front rounded vowel [y].                                                                                  | <span class="runes">ü</span>      |
| 37     | V, v        | Vilnnis (..)<br>The v in vessel. Voiced labiodental fricative [v].                                                                           |    <span class="runes">v</span>      |
| 38     | V̊, v̊ / W,w | Drev̊eth (..)<br>The w in west. Voiceless labio-velar approximant [ẘ]. Used interchangeably.                                                |  <span class="runes">w</span>        |
| 39 |       Y, y      | The y in yes.<br>Palatal approximant [j].                                                                                                    | <span class="runes">y</span>         |
| 40   | Z           | The z in zebra.<br>Voiced alveolar fricative [z].                                                                                            | <span class="runes">z</span>         |

## Table 2: Pronunciation Rules (New Script)
| Consonant Shifts | Example   | Notes |
|------------------|-----------|-------|
| 0                | Nenma     | nm → mm. "nm" is pronounced as mm (nasal m sound).                                                                  |
| 1                | Vilnnis   | nn → n. "nn" is pronounced the same as a single n.                                                                   |
| 2                | Aedir     | ae is its own rune. Diphthong [a.e]. Distinct from ai.                                                               |
| 3                | Naira     | ai is its own rune. Diphthong [aɪ], "ride". Distinct from ei.                                                        |
| 4                | Einar     | ei is its own rune. Diphthong [eɪ], "say". Distinct from ai.                                                         |
| 5                | Elnâ      | nâ is its own rune. Pronounced like “nya” in canyon.                                                                 |


## Table 3: Vowel and Diphthong Sounds

| Symbol               | Example   | Notes                                                                                                          |
|----------------------|-----------|----------------------------------------------------------------------------------------------------------------|
| ^                    | Ânthor    | The circumflex elongates vowel by double its length.                                                          |
| ˊ                    | Ŕuai      | The acute accent on a vocal or consonant suggests stress.                                                     |
| ’                    | Sa’en     | The apostrophe between vowels suggests a glottal stop.                                                        |
| ^ (after consonant)  | Kâr       | The circumflex after a consonant softens both consonant and vowel.                                            |
| H before consonants  | Khâr      | Using H before certain consonants negates the softening effect of the circumflex.                             |
| ˚ (trill marker)     | R̊uk       | Marks a consonant as trilled or rolled. Appears after the base letter. Not a diacritic, but a modifier.        |

## Invalid Accent and Diacritic Usage

1. The Accent Collision Rule
While the diacritics (˚) and (^) can exist on two consecutive letters, a letter will never carry both a circumflex (^) and an acute accent (ˊ). Such a combination is considered invalid in the script’s orthography.

2. Double Accents Across Diphthongs
Only one accent may be applied to a diphthong. Accents cannot be stacked across a diphthong, ensuring that each accented syllable receives only one accent.

3. Accent Placement on Consonants and Vowels
The acute accent (ˊ) can be placed on consonants. When placed on a consonant, the acute accent (ˊ) suggests stress. In order to stress a vowel, a circumflex (^) is placed on the vowel. This always elongates the vowel as well as stressing it.

4. Glottal Stop (’) Overriding Softening
If a glottal stop (’) is present, it will override the softening effect of the circumflex (^). For instance, in a word like Lâ’ân, the glottal stop (’) takes precedence over the softening effect of the circumflex (^) on the second vowel, ensuring that the consonant is not softened as it would typically be.

5. Invalid Diacritic Stacking
A letter can never carry both a circumflex (^) and an acute accent (ˊ) simultaneously. Combinations like Â’ê are not allowed in the script and will be considered incorrect orthographically.