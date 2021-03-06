---
title: Compilation Starts With A 'C'
date: '2014-10-07'
---

Yeah, this might be a rather simple statement, mainly because the word Compilation really truly starts with the letter: 'c'. However, the idea also extends to the C language.  Anytime a C program is built and sent off to its consumers there is a semi-complicated, definitely fiddly make/build process. This is what defines a compiled language like C or [Golang][1] from there interpreted brethren. An example of some interpreted languages would be the following: [Ruby][2], [Python][3], [Forth][4]. Is there an actual Forth "official" website? If for some reason you are human, and don't quite "grok" what Forth is, [this is a pretty good explanation][5].

So why on earth is this worth another blog post? There exists an awash of blog posts, Quora answers and miles of Wikipedia edits concerning these topics. Glad you asked. All of this hoopla can be summed up in this one [exciting NPM module called Harp][6]. Harp, if you read their website, is an exciting [static site blogging tool][7] that will save you all the trouble of running one of those WordPress things. Which, if you read and listen to much of the Internet (no worries, it is chill you [likely choose not to read][13]), is like running a third world country.

This Harp thing... It looks pretty sweet, it even runs on Javascript which is not named even after a language that isn't compiled. However, if one were to scroll 7/12ths down the page (yes we are succinct here), it would appear that this is "compiled". Compiled you might ask (if you chose to read). That seems weird, why would we need to compile things like HTML/CSS when the last time anyone checked, these things could be considered 'web native'.

Any rational person at this point would be all like: WTF? [Node Javascript][8] is like a whole server? Eh? There are even frameworks that rhyme with Rails that work on this very same platform. So why would we have to compile our static files, or site, or whatever when this can be done directly on the server? Oh, because you need to compile locally and then commit your compiled code (because that makes sense). Unless of course you just wanted to take the folder that is generated by this compilation and FTP (sorry SFTP) it to your server. All of this makes sense in 2002 but, rarely could be considered a standard in 2014.

Could this get any better you maybe asking? Well you could write all of your HTML in smaller, completely unmanageable chunks because only 50 out of every 328 web developers understands [Jade][9] enough to juggle where they are currently in that [pipe][12] field of hell.. But, no worries, Jade is way less fiddly because you don't have all of those brackets (shit, that's why I love HAML and SLIM because writing inline tags is a breeze and expected output is at an all time high). Except, when you want to include someone in the project who has no idea about Jade and tries to modify the compiled source because it just makes sense... to every web developer. Then we have trouble. Though now, how do you compile the compiled source? Yeah I don't know either. Presumably, and this is almost always a likely:

>'Because I am not smart enough.'

Ok, so there are quite a few glaring issues with compiling things when the runtime is actually a perfectly good server. However, there must be some reasons for these kind of static site generators? Sure! Pet projects, quick one offs, LaunchRock style landing pages and personal blogs are perfect use cases. However, due to the technical knowledge required for bringing new team members up to speed, their reliance on committing compiled code to the VCS repository, and their somewhat beta 0.0.1-ness these should remain within the personal realm. Also, having to wait for someone to return from [their lunch break][10] just to get something compiled must be a boon for the entire teams velocity.

Yes, [this][11]

[1]: https://golang.org/
[2]: https://www.ruby-lang.org/en/
[3]: https://www.python.org/
[4]: http://groups.engin.umd.umich.edu/CIS/course.des/cis400/forth/forth.html
[5]: http://cloudbacon.com
[6]: http://harpjs.com/
[7]: https://gist.github.com/davatron5000/2254924
[8]: http://i.imgur.com/FHWMO.gif
[9]: http://jade-lang.com/
[10]: https://gimmebar.com/view/504f465629ca15bb4b000000/big
[11]: https://the-pastry-box-project.net/ed-finkler/2014-october-6
[12]: https://en.wikipedia.org/wiki/Pipeline_(Unix)
[13]: http://cloudbacon.com/2011/12/19/People-Can-Not-Read
