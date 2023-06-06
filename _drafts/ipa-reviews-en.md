---
layout: post
tags: writing
title: draf-ipa-en
---

I was quite annoyed when the font I visually liked didn't display IPA characters properly (uncomfortably placed diacritics, tie-bars that cut off the letters they're attached to, and so on). Instead of continue the writing process, which is certainly more important, I was engrossed in choosing a visually and technically beautiful new typeface instead. No doubt substantial progress of the Krewi Language documentation is a rare sight.

The idea of this compilation was sparked when I noticed that my list in my notebook titled "IPA fonts choices" was starting to add up to a sizable amount. It was also motivated by the fact that how enormous the amount of time and knowledge needed to find and handpick through millions of typefaces on the internet that has at least has a sizable IPA block filled in one of the set available. Most of font repository has no label to indicate IPA either. As such, I thought It'd be nice to make a write up about this to help myself in the future and, hopefully, anyone who happens to read this article.

## Introduction: Technical details

{% include heyo.html content="Nerd stuff ahead, don't read!" %}

As a transcription system, IPA aims to precisely represent speech sounds into visual, written form. The problem is that human vocal organ are so flexible and complex that those all alone are able to create a multitude of different, discernible sound. IPA, being alphabetical,[^1] was faced with the daunting task of representing those.[^2] Therefore, as latest changes in 2005, 107 letters (including IPA letters readily available in the Latin and Greek) needed to be considered for placement in the IPA block. The large number of entirely new letters that needed to be drawn from scratch made a lot of type designers reluctant to incorporate IPA as it requires additional specialized understanding and specific measures to design and accomodate IPA features.

[^1]: Another interesting approach to overcome this problem is to treat human voice segments as combinatorial. Many IPA alternatives such as [UPA](https://omniglot.com/conscripts/upa.htm), [Musa Alphabet](https://musa.bet/home.htm), and [UPFA](https://redd.it/137skmk) are based on this approach and take featural system as visual basis.
[^2]: This luxury (being surrounded by [Unicode](https://en.wikipedia.org/wiki/Unicode)-supported devices) was not experience by those in the past. Hence, systems like [X-SAMPA](https://en.wikipedia.org/wiki/X-SAMPA) (SAMPA derivative) were constructed as a "hack" of an environment that mostly only supported [ASCII](https://en.wikipedia.org/wiki/ASCII). Therefore, the burden held by X-SAMPA is even greater as it has to represent a large number of voice segments with a mere 95 characters (compared to Unicode v15 which supports more than 800,000 characters. At the time of writing, only 149,186 characters slot have been filled).
