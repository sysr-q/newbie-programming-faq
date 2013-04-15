Newbie Programming FAQ
======================

[google]: https://google.com "The ultimate resource!"
[github]: https://github.com "Social programming"
[wikipedia]: https://en.wikipedia.org

## Note:

### Hey, that seems a bit biased!
What, me? Writing a biased FAQ guide? I never!  
Well, you're probably right. I'm not the ultimate resource for everything. I'm only writing from what I know personally, or what I've researched.  
If you disagree with something, point it out and I'll do more research on that topic, or send in a pull request with corrections and we'll see what we can work out.

### How do you know what questions are commonly asked?
Good question; it's because I frequent many of the programming sections (`Coding and Programming`, `PHP` and `Python` mostly, with stops into `.NET languages`, `Java` and `Batch, Bash & CLI`) on various sites.  
This is compiled from the many questions that I come across daily.  
__Every day__ these threads are popping up in the various sections, and they're just a nuisance.

### What if someone posts these questions anyway?!
That's a good point. Often, these users don't seem to understand that the internet is widely and easily searchable, and it's almost guaranteed someone has asked their exact question before.  
What should we do when that happens? You can do a variety of things, here's a few:

* Link them to the __search__ feature of whatever forum/site you're using.
    * If the site doesn't have a search feature, send them to Google, and explain the `site:xyz.com` filter!
* Provide links to various threads or topics where this question has been asked and answered before.
    * Mention that searching will often times turn up answers, and they should consult that first.
* Send them a link to this document!
    * Nothing wrong with a bit of self promotion, right?

### They're just ignoring me!
Don't worry, newbies often take a bit of nudging to get them pointed in the right direction!  
If you just follow the steps above, and they're continuously provided with the same steps time and time again, it's bound to sink in!

### What should I do if I've got ideas or questions that you don't cover?
Open up an issue on the GitHub repository, or send in a pull request.  
I published this on a git repo specifically so that the community can join in and help make this guide complete and informative.

With that in mind, let's get straight to it!

**********

_For now, I've split this into sections for general FAQs and language specific ones._

# Tips and Tricks

## How do I do X or Y with this language?
Have you checked [Google][google]? Seriously, that is the single best resource for anything. Hell, you have the entire __internet__ at your disposal!

For example:  
Suppose that I want to split a sentence into pieces (on spaces) and see if any of the words are `newbie`, using Python, I might search:

* `python split string on space`
* `python check if string in sentence`

These would probably lead me to the Python core documentation, which would give clear and concise examples on each of these.

## Can you guys help me learn?
The only person who can help you learn is __you__. Others can guide you along the path to learning (by giving links to decent guides, for example), but the only person who can ultimately help you learn is yourself.  
You have to really commit to learning to program, because - as I touch on later - if you don't want to learn to program, or you're just in it to make quick cash, you won't be able to learn as well as someone else who is learning for their love of programming, or their wish to create an application to cover certain requirements.

## What library should I use to achieve X?
It depends on your language, really!  
A good place to start for this - as with anything, really - is [Google][google].
Another great place is [GitHub][github]. Between these two, you should be able to cover anything.

If you use Python, you're spoiled for choice! You can find a module for just about everything - seriously - on [PyPI](https://pypi.python.org/pypi). If it can be done, someone has probably made a module and put it up for download there.  
If you use PHP, [GitHub][github] is one of the best places (in my opinion) to find projects to cover your needs. Do a search, filter to repos written in PHP and you're set!

**********

# General FAQs

## Which editor should I use?
Most of the time, this will be met with responses from a few different people, which I'll run over here:

### The Super Do-It-All IDE User (Extreme #1)
These people depend (usually) on a flat out, amazing feature-packed IDE, and they swear by it.  
__"If you don't use an IDE,"__, they'll say, __"you're missing out!"__

### The Super Minimalist (Extreme #2)
These people will swear by nothing more than a command line __vim__ or __Emacs__ setup.  
__"Why would you need anything else?"__, they ask.  
They're power users, and feel right at home on a command line, navigation with their favourite _hjkl_ keys, throwing out more commands than you can make sense of.

### The In-between
They'll jump between the two extremes, or settle somewhere in the middle.  
Commonly seen using something like _Notepad++_, _Sublime Text 2_ or their GNU/Linux default editor (Geany, Kate, etc).

The truth of the matter is, __it's entirely up to you__! Nobody can tell you what is best; it's like a car, if you think about it.  
One man might swear by the Porsche, another will say that if you need more than a 2005 Honda you're stark mad, with someone else just saying they drive whatever works.

Try out a few, and really have a feel around. You might be surprised what you click with.

## I'm new, which language is best?
There isn't particularly a _best_ language in any sense. Some are more suited to a particular task than another.  
Think of programming as a being a carpenter, and the languages are your tools. Sure, you can hammer in a nail with a spanner, but why would you when you've got a perfectly good hammer right there?

What I'm saying is, there isn't a _best_, there's just _preferred_ languages. Some people are biased because of their love for certain languages (like my love for Python), but in general, you pick the language which works best for your current project or requirements.

Some languages which people suggest frequently for new programmers are:

* [Python](https://python.org)
    * A beautifully written all round language, which excels in scripting
    * __Interpreted__, so definitely not the fastest language out
    * Usable for for just about anything:
        * Web projects (with `Flask`, `Django` or others)
        * Servers (with `Twisted`, `gevent` or others)
        * Web crawlers (with `requests` and `urllib` (plus `urllib2`))
    * A __gigantic__ amount of modules available online, easily installable via [PyPI](https://pypi.python.org)
    * Has an __amazing__ community available
* [Ruby](https://ruby-lang.org)
    * Designed to be human readable, which it definitely achieves
    * Easy to read, easy to write, easy to distribute and just a nice language to work in
    * __Interpreted__,  so definitely not the fastest language out
    * Usable for just about anything, with similar libraries available as Python
    * Has an __amazing__ community available
* [PHP](http://www.php.net)
    * Designed by a man who self-describes as a man who ["hates programming, but loves solving problems"](http://en.wikiquote.org/wiki/Rasmus_Lerdorf)
    * Wide support, since it's got interpreters out the wazoo for most web servers
    * Has lots of gotchas and caveats, as documented in [PHP: A fractal of bad design](http://me.veekun.com/blog/2012/04/09/php-a-fractal-of-bad-design/) by [@eevee](https://github.com/eevee)
    * __Interpreted__, so it's slow as all heck
    * Probably a poor choice for a first language
    * Interfaces with HTTP quite well, since it's basically designed for web applications
    * Not really usable for anything but websites
    * The community is somewhat lacking, but StackOverflow is a good place for PHP stuff
* [VB.net](http://msdn.microsoft.com/en-us/vstudio/hh388573.aspx)
    * Designed by Microsoft, specifically targeting the Windows operating system
    * Usable on other operating systems __sometimes__ via workarounds such as compat. layers like Wine or Mono.
    * __Compiled to IL code__, so whilst fast, it's not Native Fast (TM). ([Source](http://stackoverflow.com/questions/6002955/visual-basic-net-compiled-or-interpreted))
    * In my opinion, a poor choice for a first language
    * The community (in my opinion) is alright. Not as amazing as Python, not quite lackluster like PHP; somewhere in-between
* [Java](http://docs.oracle.com/javase/tutorial/java/)
    * Object oriented to boot.
    * Comes with an amazing amount of getters and setters (whether you enjoy this is personal preference)
    * __Interpreted__ by the JVM (Java Virtual Machine). It's not quite as slow as an interpreted language, but not quite as fast as a compiled language.
    * Used in many enterprise level projects, so an understanding of it can't really hurt anyone.
    * The community around Java is fairly nice, and as per PHP, StackOverflow is a great place for Java things

## I want to learn to program to make a game, RAT, operating system, or some other large project.
Stop right there, criminal scum!  
Whilst sometimes it's alright to start learning a programming language with a large project in your horizons, that's not a great way to learn initially.  
From my personal experiences, if you try to learn to program purely to complete a large project (which might take hundreds of man hours from a professional firm) you'll get sick and tired of programming fairly quickly, and burn out.

Sure, it works for some people if they're either working through a book which teaches you programming concepts whilst also working towards a game, or they're already a programmer; often times it just leads to sadness.  
Start programming because you want to have tools under your belt to help with various problems, not because you think you can make money, or get fame via it.

If you play sport because you enjoy it, getting sponsorship from a large group is great! Money, fame, all of that; but if you play sport purely because you want money, fame or anything related, you're just going to become disappointed when it inevitably doesn't work out.

## Hey, I need help making the next Facebook, Twitter or (CURRENT FAD HERE)!
Sorry to say, but that's probably not going to just happen. Many of the larger websites we use these days started up years ago when they were fresh ideas.  
Microblogging, sharing videos or sending pictures? That's all been done time and time again now; so it's hard to get your idea picked up by heaps of users.

You're certainly free to create your own version of whatever website you so desire, but don't get too disappointed when it's not used by millions of users daily.  
It takes time for a new idea, or an improvement over old projects to catch on, if they ever do; Don't lose hope if you're really interested in it, but don't stress if you're not instantly picked up and gain the usage Facebook does.

**********

# Glossary

* `IDE` - __Integrated Development Environment__
    * _An integrated development environment (IDE) is a software application that provides comprehensive facilities to computer programmers for software development. An IDE normally consists of a source code editor, build automation tools and a debugger._ (from [Wikipedia][wikipedia])
    * Examples are: Eclipse, NetBeans, Cloud9, Visual Studio
* `foo`, `bar`, `baz` - Placeholders for developers!
    * These are just key words which are often used in code snippets, used as place holders. They signify things which should be replaced with actual variables to achieve whatever the purpose of the snippet is.
    * Sometimes they're variable names, sometimes they're string values, and sometimes they're aliens - well not really.
* `regex` - Regular Expressions
    * _A regular expression is a specific pattern that provides concise and flexible means to "match" (specify and recognize) strings of text, such as particular characters, words, or patterns of characters._ (from [Wikipedia][wikipedia])
    * Examples are: `^#([a-fA-F0-9]{3}|[a-fA-F0-9]{6})$`, `(?:[^/]+)/$`
