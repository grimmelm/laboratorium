---
layout: post
title: Spyware vs. Spyware
date: '2020-04-07T13:34:28-04:00'
tags:
- scholarship
tumblr_url: https://2d.laboratorium.net/post/614760048014557184/spyware-vs-spyware
---
I’m happy to announce a little non-coronavirus news. I gave a lecture at Ohio State in the fall for the 15th anniversary of their newly renamed [Ohio State Technology Law Journal](https://moritzlaw.osu.edu/ostlj/). It was a great program: [Mary Anne Franks](https://www.law.miami.edu/faculty/mary-anne-franks) gave the other lecture and there were some unexpected but fascinating connections between our talks. My remarks have been going through the editorial pipeline, and just today the student editors emailed me the final PDF of the essay. And so I give you [_Spyware vs. Spyware: Software Conflicts and User Autonomy_](https://james.grimmelmann.net/files/articles/spyware-vs-spyware.pdf).

By remarkable coincidence, my talk started with … a massive Zoom privacy hole.

> This is the story of the time that Apple broke Zoom, and everybody was surprisingly okay with it. The short version is that Zoom provides one of the most widely used video-conferencing systems in the world. One reason for Zoom’s popularity is its ease of use; one reason Zoom was easy to use was that it had a feature that let users join calls with a single click. On macOS, Zoom implemented this feature by running a custom web server on users’ computers; the server would receive Zoom-specific requests and respond by launching Zoom and connecting to the call. Security researchers realized that that web pages could use this feature to join users to Zoom calls without any further confirmation on their part, potentially enabling surveillance through their webcams and microphones. The researchers released a proof-of-concept exploit in the form of a webpage that would immediately connect anyone who visited it to a Zoom video call with random strangers. They also sketched out ways in which the Zoom server on users’ computers could potentially be used to hijack those computers into running arbitrary code.
> 
> After the story came to light, Apple’s response was swift and unsparing. It pushed out a software update to macOS to delete the Zoom server and prevent it from being reinstalled. The update was remarkable, and not just because it removed functionality rather than adding it. Typical Apple updates to macOS show a pop-up notification that lets users choose whether and when to install an update. But Apple pushed out this update silently and automatically; users woke up to discover that the update had already been installed—if they discovered it at all. In other words, Apple deliberately broke an application feature on millions of users’ computers without notice or specific consent. And then, six days later, Apple did it again.
> 
> There is a lot that could be said about this episode; it illuminates everything from responsible disclosure practices to corporate public relations to secure interface design for omnipresent cameras and microphones. But I want to dwell on just how strange it is that one major technology company (AAPL, market capitalization $1.4 trillion) deliberately broke a feature in another major technology company’s (ZM, market capitalization $24 billion) product for millions of users, and almost no one even blinked. We are living in a William Gibson future of megacorporations waging digital warfare on each other’s software and everyone just accepts that this is how life is now.

Here is the abstract:

> In July 2019, Apple silently updated macOS to uninstall a feature in the Zoom webconferencing software from users’ computers. Far from being an abberation, this is an example of a common but under-appreciated pattern. Numerous programs deliberately delete or interfere with each other, raising a bewildering variety of legal issues.
> 
> Unfortunately, the most common heuristics for resolving disputes about what software can and cannot do fail badly on software-versus-software conflicts. Bad Software Is Bad, which holds that regulators should distinguish helpful software from harmful software, has a surprisingly hard time telling the difference. So does Software Freedom, which holds that users should have the liberty to run any software they want: it cannot by itself explain what software users actually want. And Click to Agree, which holds that users should be held to the terms of the contracts they accept, falls for deceptive tricks, like the the virus with a EULA. Each of these heuristics contains a core of wisdom, but each is incomplete on its own.
> 
> To make sense of software conflicts, we need a theory of user autonomy, one that connects users’ goals to their choices about software. Law should help users delegate important tasks to software. To do so, it must accept the diversity of users’ skills and goals, be realistic about which user actions reflect genuine choices, and pay close attention to the communicative content of software.

