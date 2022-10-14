---
layout: post
title: The GPL Is Almost an All Writs Canary
date: '2016-04-15T11:39:18-04:00'
tags: []
tumblr_url: https://2d.laboratorium.net/post/142848414775/the-gpl-is-almost-an-all-writs-canary
---
_The following is a very tentative analysis. If I have misread or misapplied the GPL, please let me know in the comments!_

Indulge me. Suppose that iOS were licensed under the [GNU GPL version 2](http://www.gnu.org/licenses/old-licenses/gpl-2.0.en.html) because it were built on top of the Linux kernel.<sup id="fnref:1"><a href="#fn:1" class="footnote-ref" role="doc-noteref">1</a></sup> Might that have changed how the San Bernadino case went down–or how a future case would? Perhaps

The court in the San Bernadino relied on the All Writs Act to [order](https://assets.documentcloud.org/documents/2714001/SB-Shooter-Order-Compelling-Apple-Asst-iPhone.pdf) Apple to provide “reasonable technical assistance” to allow the FBI to submit guessed passwords to the iPhone automatically and rapidly, and without wiping the phone after too many incorrect guesses. In particular, the court suggested that Apple could comply by

> providing the FBI with a signed iPhone Software file, recovery bundle, or other Software Image File (“SIF”) that can be loaded onto the SUBJECT DEVICE. … The SIF will be coded by Apple with a unique identifier of the phone so that the SIF would only load and execute on the SUBJECT DEVICE.

According to Apple, this order was objectionable in two respects: (1) Apple would need to create a custom version of iOS, and (2) Apple would need to use its private keys to digitally sign that custom version. Apple called this custom version “govtOS,” so I will, too. In Apple’s view, both (1) and (2) impermissibly conscripted Apple, and both (1) and (2) would have weakened iOS security in general.

Back to the license. Under the GPL, govtOS would be a “a work based on the Program”: a derivative work of the GPL-licensed components of iOS. The GPL allows licensees like Apple to “modify your copy or copies of the Program” and to “copy and distribute such modifications,” but only if they also provide “the complete corresponding machine-readable source code.” So Apple could not, without violating the GPL and becoming a copyright infringer, provide govtOS only as object code and not also as source code.

This is almost, but not quite, an All Writs canary. If Apple were required to post the source to govtOS publicly, then the fact that govtOS had been created and what it did would become public. If the All Writs order compelling Apple to create govtOS were subject to a gag order about revealing this fact, then Apple would be on the horns of a dilemma: it could either defy the court order or violate the GPL. The only way to comply with the All Writs order would be to become a copyright infringer.

At the very least, this is an argument against granting the order in the first place. Entering into a legally enforceable obligation to speak publicly about one’s compliance with government orders increases the burden those orders impose. A court might not be entirely sympathetic where a party simply enters into a contract or makes a promise to users, since the purpose of taking on such obligations is so obviously simply to thwart future gag orders. But where the requirement to speak up stems from one’s software-license obligations, a court that orders an Apple to code govtOS and shut up about it would effectively be prohibiting companies from using source-disclosing copyleft licenses without a substantial risk of being unable to comply.

Now, such a court might also opine that the company is protected from infringement liability because use of the software pursuant to a court order is fair use. But such a statement would be dictum, since the copyright owner isn’t before the court. For what it’s worth, the GPL is quite clear that as far as it is concerned, court orders do not excuse compliance with the license:

> If, as a consequence of a court judgment or allegation of patent infringement or for any other reason (not limited to patent issues), conditions are imposed on you (whether by court order, agreement or otherwise) that contradict the conditions of this License, they do not excuse you from the conditions of this License. If you cannot distribute so as to satisfy simultaneously your obligations under this License and any other pertinent obligations, then as a consequence you may not distribute the Program at all.

So I think a source-disclosing copyleft license could effectively be an All Writs canary. But the GPLv2, as I understand it, isn’t quite. The issue is that the source code need not be disclosed to the public at large. Instead, the licensee need merely “_Accompany_ [the modified software] with the complete corresponding machine-readable source code” (emphasis added). True, there is also an option to make “a written offer, valid for at least three years, to give any third party, for a charge no more than your cost of physically performing source distribution, a complete machine-readable copy of the corresponding source code”–but it would be Apple’s choice whether to make such an offer rather than bundle the source code with govtOS when turning it over to the FBI. Thus Apple would need to give the govtOS source code only to the FBI, not to the world at large. (For essentially the same reason, [GPL version 3](http://www.gnu.org/licenses/gpl-3.0.en.html) isn’t an All Writs canary, either.)

This is where the difference between (1) creating govtOS, and (2) signing it, comes back in. Even with the source code, the FBI would still need Apple’s private keys (or some other vulnerability) to install it on targeted iPhones. Version 3 of the GPL is clearer and more precise on this point. Under it, the signing is a matter of “Installation Information”:

> “Installation Information” for a User Product means any methods, procedures, authorization keys, or other information required to install and execute modified versions of a covered work in that User Product from a modified version of its Corresponding Source. The information must suffice to ensure that the continued functioning of the modified object code is in no case prevented or interfered with solely because modification has been made.
> 
> If you convey an object code work under this section in, or with, or specifically for use in, a User Product, and the conveying occurs as part of a transaction in which the right of possession and use of the User Product is transferred to the recipient in perpetuity or for a fixed term (regardless of how the transaction is characterized), the Corresponding Source conveyed under this section must be accompanied by the Installation Information. But this requirement does not apply if neither you nor any third party retains the ability to install modified object code on the User Product (for example, the work has been installed in ROM).

govtOS is an “object code work … in, or with, or specifically for use in, a User Product.” So the question is whether “the conveying occurs as part of a transaction in which the right of possession and use of the User Product is transferred to the recipient in perpetuity or for a fixed term.” Ironically, while the government already had “the right of possession and use of the User Product,” it did not acquire those rights and govtOS in the same “transaction.” Rather, when Apple sold the iPhone initially, in this counterfactual world, it would have needed to provide the Installation Information then–so the government would already have access to the necessary signing keys from that disclosure. The net result is that because iOS can be updated at all, version 3 of the GPL takes the FBI’s side when it comes to the code signing half of the story. If you can flash your own custom OS onto a device–technically and legally–so can the feds.

All of this is a bit of a flight of fancy, given that iOS is not, never has been, and is not likely ever to be licensed under the GPL. But I found it an interesting exercise, since the interactions between free-and-open-source licensing terms and the kind of compelled coding issues at stake in the iPhone cases are not at all obvious or intuitive. Given that law enforcement shows every sign of wanting to compel substantial assistance from software, cloud, and consumer-device companies in the future, it seems like it would be worthwhile to think through the issues in more detail.

* * *

* * *

1. 

This is obviously a bit far-fetched, but it’s not entirely absurd. iOS is based in part on members of the BSD Unix family, so parts of it are BSD-licensed.&nbsp;[↩︎](#fnref:1)

