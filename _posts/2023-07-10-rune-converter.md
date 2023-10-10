---
layout: post
title:  "Converting runes to latin and vice versa"
date:   2023-10-10 21:56:17 +0100
author: Demecate
type:   devblog
---

I have created https://runes.redcity.ink in order to convert runes to latin and vice versa. 
After working on the runes for a few months, I finally felt ready to publish the language. If you would like to skip the details click here: [TLDR](#tldr)

# The Language and the Alphabets
The language calls itself "carving" as people carved the letters on stones and slabs in the past, before the first word was ever spoken. 
Today the runic alphabet is called The Forgotten Alphabet,
and there are two ways to write down speech, either in the forgotten alphabet or the new alphabet.

The new alphabet uses characters such as circumflex, ö, ı, ü in addition to the English alphabet. The converter is mostly for myself and our devs so that
we can write in the runic alphabet or convert the runes to latin when needed. However, if you'd like to play around with it you are more than welcome! 

# Creating the Fonts

After designing the runes themselves (and their logic), we had to create a font in order to represent the characters in a digital environment. For this I have used [Calligraphr](https://www.calligraphr.com/) and Adobe Illustrator. Currenty in order to fully utilise the forgotten alphabet you should use a Turkish keyboard layout (or any other layout that has ı, ö, ü). I initially wanted to use different letters but these were far easier to work with. I might change them in the future. 

Currently, all of the runic characters in the font are mapped to numerical keys (for coding convenience) except the space character, which is mapped to the space key. You can find these posts on the new [page](https://runes.redcity.ink) and the page should prompt you if you don't have the fonts installed. The converter would not work without the fonts installed.

I have taken the most (seemingly) convenient path for me, but I kind of regret my approach as I realised later on that it was a very spaghetti way. I am sure there are much better ways to design fonts --and if that is something you have done and are good at and you'd like to help out, please get in touch.


# TLDR

We have a webpage that converts runes into latin and vice versa. 

The converter still has a few bugs, but it is able to:

- Convert latin to the new alphabet Ex:(aa -> a, gg -> g̊ -> rr -> r̊)
- Convert latin to the forgotten alphabet (runes)
- Convert forgotten alphabet(runes) back to latin

You can find it [here](https://runes.redcity.ink).

In order for it to work, you would need to install a font.

# Thanks

Thanks to everyone who has been involved in this project helping me on linguistics, design and coding. I will add your name under this when you want me to.