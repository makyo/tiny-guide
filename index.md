---
layout: default
title: Makyo's Tiny Guide to MUCKing
gh_user: makyo
gh_repo: tiny-guide
---

This is meant mostly as a cheat-sheet, and is broken down into a list of tasks, each of which will show a command and what it produces!

## Talking
`"Hey there! Long time no see!` or `say Hey there! Long time no see!`

> Makyo says, "Hey there! Long time no see!"
    
## Posing (showing an action)
`:swishes her tail excitedly.` or `pose swishes her tail excitedly` or `po swishes her tail excitedly`

> Makyo swishes her tail excitedly.
    
## Talking privately (when in the same place)
`wh foxface=Hey, you're really cute, you know that?` or `whisper foxface=Hey, you're really cute, you know that?`

Makyo sees:
    
> You whisper, "Hey, you're really cute, you know that?" to Foxface.
    
Foxface sees:
    
> Makyo whispers, "Hey, you're really cute, you know that?" to you.
    
## Posing privately (when in the same place)
`wh foxface=:ruffles your ears.` (or `whisper` as above)

Makyo sees:
    
> You whisper, "Makyo ruffles your ears." to Foxface.
    
Foxface sees:
    
> Makyo whispers, "Makyo ruffles your ears." to you.
    
## Talking privately (when in different places or the same place)
`p catbutt=Love the outfit!` or `page catbutt=Love the outfit!`

Makyo sees:
    
> You page, "Love the outfit!" to Catbutt.
    
Catbutt sees:
    
> Makyo pages, "Love the outfit!" to you.
    
## Posing privately (when in different places or the same place)
`p catbutt=:puts a bow on your tail.` (or `page` as above)

Makyo sees:
    
> You page-pose, "Makyo puts a bow on your tail." to Catbutt.
    
Catbutt sees:
    
> In a page-pose to you, Makyo puts a bow on your tail.
    
## `page` and `whisper` tips

* You can leave off the name (`p =Hi again!`) and it will page or whisper whoever you paged or whispered to last.
* You can page more than one person at a time, just separate their names with spaces (`p catbutt foxface=:introduces you two`)
* You can page or whisper to the last person you paged or whispered to with `#r`. If you did so with multiple people, `#r` will only do the first, and `#R` will do all.
    
## Looking at someone
`l foxface` or `look foxface`

Makyo sees:
    
> Foxface is beautiful, simply stunning. They wrote all this stuff about themselves.
    
Foxface sees:
    
> &lt;Makyo just looked at you&gt;
    
## Finding out what someone's into
`wi foxface` or `wixxx foxface`

```
-- WhatIsZ Extended V1.0.0.1 WF ------------------------------[ Focused View ]
Foxface        bisexual biting bondage bottom public shy emasculation
               switch Male Black fox
-------------------------------------------------------- by K'T/AnnonyMouse --
```
    
*NB this is for Tapestries. On other MUCKs, `wi` shows general interests and `wixxx` adult interests*
    
## Making changes to your character
`editplayer`

You'll be presented with a menu that will help you set up your character.
