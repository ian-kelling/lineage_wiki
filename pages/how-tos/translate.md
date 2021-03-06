---
sidebar: home_sidebar
title: How to translate
folder: how-tos
permalink: translate-howto.html
tags:
 - how-to
---

## How to translate

We use [Crowdin](https://crowdin.com/projects/LineageOS) as our translation system. To submit translations, create an [account](https://crowdin.com/join), click the desired language and apply as translator. Once you are accepted, you can click through the various files and suggest translations.

### Difference between LineageOS and LineageOS AOSP

On [Crowdin](https://crowdin.com/projects/LineageOS) you will notice two different projects:

 - The ``LineageOS`` project contains translations for LineageOS' additional features and applications for languages supported by AOSP.
 - The ``LineageOS AOSP`` project is for languages not part of the upstream Android sources. It contains the strings for LineageOS' features and additions but will also allow for translation of the rest of the OS.

### My language is not there and I have checked several times

You seem to speak a language which nobody else does... or there has just been the lack of someone willing to provide support. Contact one of the managers so we can support you by adding your language as well.

## I have translated a lot, how do I get these to my device now?

There is (or should be) at least one proofreader for each language (you can apply, if not). Proofreaders will look through the strings and validate those which they think are fitting the context and are of a high-enough quality. In the event that you do not see an active review or acceptance of your (or alternative) suggestions, you can contact one of the proofreaders via the sidebar on the right. To do so, simply type "@" followed by the name and then add the message (e.g. "@NameHere: Please look through my translations on this file").  
After the strings have been validated, a scripted job is run (by one of the [Managers](http://wiki.lineageos.org/contributors.html#translations-managers) to import the strings to [Gerrit](https://review.lineageos.org). After a successful test build they get merged to source code and will be part of every new official build.

{% include tip.html content="You can check who the proofreader is for your language on the [Contributors](http://wiki.lineageos.org/contributors.html#translations-proofreaders) page." %}

## Correcting wrong strings

### Translated strings

Sometimes you will notice translated strings which seem to be slightly different from what you'd expect or simply wrong. There are various reasons to how this can happen, but still, the only relevant thing is how to improve the translation. Just suggest your translation like you would do for any untranslated string. After saving it you will have the possibility to "Notify the proofreader".

{% include note.html content="If you feel like the proofreader (who is a volunteer as well) is not doing a good job or isn't active anymore, feel free to send him a message or notify one of the [Managers](http://wiki.lineageos.org/contributors.html#translations-managers) about it." %}

### Original strings

There is no guarantee the original strings you want to translate are perfect. If you notice an issue there, use the side bar and mark the field "issue", then type some info on what you think is wrong. If the mistake is only minor, correct this error in your translation, and submit it.
