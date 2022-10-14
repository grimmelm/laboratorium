---
layout: post
title: A Few Thoughts on Cisco v. Beccela’s
date: '2019-08-27T15:10:15-04:00'
tags:
- law
tumblr_url: https://2d.laboratorium.net/post/187310633210/a-few-thoughts-on-cisco-v-beccelas
---
Rebecca Tushnet [blogged](https://tushnet.blogspot.com/2019/08/first-sale-doesnt-cover-hardware.html) a trainwreck of a copyright opinion in [_Cisco Systems, Inc. v. Beccela’s Etc._](https://www.courtlistener.com/recap/gov.uscourts.cand.321659/gov.uscourts.cand.321659.105.0.pdf) from the Northern District of California. The software-licensing caselaw was not good, but this is one of the most confused opinions I’ve seen.

In brief, Cisco sells networking devices through a network of authorized dealers. The defendants allegedly sell Cisco devices outside of these authorized channels. Cisco sued on a variety of theories, including copyright infringement. In response, the defendants claimed they were making legal first sales.

Ninth Circuit caselaw (see [_Vernor_](https://scholar.google.com/scholar_case?case=10742056384168408518), [_Psystar_](https://scholar.google.com/scholar_case?case=6108853270461323983), and [_Christenson_](https://scholar.google.com/scholar_case?case=13518864802311439556)) has held that first sale doesn’t apply to software distributed on CD-ROMs or DVDs which are “licensed” rather than “sold,” and use a messy multi-factor test to determine whether a given shiny plastic disc is licensed or sold. The defendants here argued that the result should be different where the software is “embedded in hardware,” but the court disagreed that this made a difference. “The Ninth Circuit in these cases did not distinguish the first sale doctrine’s application between software and hardware … .” As a result, “[T]he first sale doctrine does not apply to software licensees even when the software is embedded in lawfully purchased hardware … .”

To which I can say only, _what does the court think that software IS_?

<figure class="tmblr-full" data-orig-height="136" data-orig-width="320" data-orig-src="https://i.makeagif.com/media/3-12-2016/zfgpSi.gif"><img src="https://64.media.tumblr.com/30233ee11709d9d560d9c26e78248ca3/9948b0cdc096719c-b7/s540x810/b8332dbece7e7209821848225d55c7a4d701f43a.gif" alt="Zoolander: The files are in the computer?!" style="align:auto;display:block;" data-orig-height="136" data-orig-width="320" data-orig-src="https://i.makeagif.com/media/3-12-2016/zfgpSi.gif"></figure>

“Software” could refer to the information in a program – the sequence of bits or characters – or it could refer to a specific physical instantiation of the program – a chip, printout, or other object encoding that information. In copyright terms, the former is a “work”; the latter is a “copy.” Cisco has a copyright in the work, and we can assume that the copyright has never been validly licensed to the defendants. But in first sale, that’s irrelevant. If I’m “[the owner of a particular copy … lawfully made](https://www.law.cornell.edu/uscode/text/17/109),” then I can distribute that copy regardless of whether I have any license from the copyright owner. That’s what first sale is. The reason that _Vernor_ and other cases rejected the application of first sale is that the _copy_ had been licensed rather than sold: that messy multi-factor test tries to figure out what rights the possessor has over a particular shiny plastic disc. For example, does the copyright owner have the right to demand the shiny plastic disc back? If so, then the possessor may not be an “owner” of that “particular copy” and so first sale may not apply.

This reasoning doesn’t on its face distinguish between shiny plastic discs and computer hardware. But that doesn’t mean the two cases are the same. It’s right there in the _Beccela’s_ opinion. In fact, it’s right there _in the same sentence where the court announces its conclusion_. Cisco’s software isn’t just “embedded in hardware”; it’s “embedded in _lawfully purchased_ hardware,” in the court’s own phrase. That ought to end the case. If the hardware is lawfully purchased (note: “purchased” and not “licensed”), then the defendants are owners of the copies of the software and have full first sale rights. Remember: “copies” are “[material objects … in which a work is fixed](https://www.law.cornell.edu/uscode/text/17/101),” a definition that includes both shiny plastic discs and dense arrays of transistors.

The court here honestly seems to believe that software can somehow be “embedded” in hardware without the hardware being a copy of the software, as though a file were in the computer but not of it. But there is no such thing. That is what it _means_ to store digital information in a thing: the physical structure of the thing becomes an encoding of the thing. Or, in copyright terms, a copy is a physical thing “from which the work can be perceived, reproduced, or otherwise communicated, either directly or with the aid of a machine or device.” That’s how software works.

To be fair, I don’t think that courts in previous first-sale and software-licensing cases have been terribly careful about the work/copy distinction or about what software is. The opinions cited in _Beccela’s_ are full of sloppy language that seems to invite this result. But that language was unnecessary; you could come out the same way in a DVD software first sale case while being careful about your terminology. _Beccela’s_ takes these unintelligible fictions about how software works and turns them into an actual holding that is essential to the outcome of the case. It is rare to see the confusion at the heart of modern software copyright licensing so plainly stated.
