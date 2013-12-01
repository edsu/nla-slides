Introduction
------------

Thanks very much for inviting me to NLA to learn more about all the stuff you 
are doing here. I was just over at the excellent NDF conference in Wellington, 
New Zealand last week.  Tim Sherrat (who I have a bit of a nerd crush on) 
noticed I was going to be in Wellington, and he kindly worked with 
Marie-Louise Ayres to bring me here today. Many thanks.

A little bit about me, I am a software developer working at the Library of 
Congress in the United States. The Library of Congress is the de facto 
national library of the US. It's the closest we have to something like the
National Library of Australia. I work in a digital preservation group there of 
about 20 people, which we call the Repository Development Center.

We've had a lot of debates over the years about what a repository is, but 
we've pretty much settled on the notion that the library as a whole is the 
repository, and our role is to fascilitate the development of software that 
helps the library do its work with digital content. I think people still 
struggle with what a digital repository should and shouldn't do, because 
practical requirements around digital content are still relatively new. 

My work has mostly focused on the role that access plays in digital 
preservation, specifically the Web.  A few years ago the RDC had a retreat to 
talk about what our group does in the context of digital preservation. 
We ended up having an interesting debate about whether our group should even
think about access, since we are a digital preservation group. 

**slide**

During that debate my colleague David Brunton remarked that digital 
preservation is access...in the future.  The implication here is that if you 
are not providing access to digital objects, maybe you're not really preserving 
them. Or as Matt Kirschenbaum says in his recent article The .txtual Condition:

> ... the preservation of digital objects is logically inseparable from the act of their creation -- the lag between creation and preservation collapses
completely, since a digital object may only ever be said to be preserved if it
is accessible, and each individual access creates the object anew.

The Web
-------

So, access is really important to me, and in particular Web access because of 
its ubiquity.  Many of us carry around windows into the Web in our pockets. 
5 years ago Google estimated that the Web was made up of 1 trillion unique 
URLs. 

**slide**

Wolfram Alpha says that 1 trillion is 3.3 times the number of stars 
in our galaxy. It's also 9 times the number of people who have ever lived. 
Interestingly, it's only 5% of the total number of red blood cells in the 
human body. How do we even begin to think about how our collections fit 
into that information space?

One of the things I really appreciated learning about at NDF was Simon Tanner's
Balanced Value Impact Model. I believe he's doing a workshop here tomorrow about
it, and if you have the opportunity to attend I highly recommend it.  I am 
just learning about the model now, so I'm certainly not an expert, but the key
thing I took from his presentation was that we need to do a better job of 
measuring the impact of what we do. By impact Simon means how what we do
influences the lives of others, either in positive or negative ways. Simon 
stresses that discipline is needed to measure impact along the way. Statistics 
like, we've had 5 million hits on our website today, or we have 28 million 
objects in our repository, are simply measures of scale, but not of impact ... 
and impact is what actually matters. Are we making people's live's better? 
Are we making them worse? Are we not impacting people's lives at all?

When Tim invited me here, I thought I would talk about some of my experiments or
toys I've created to explore how our collections fit into Wikipedia and the 
larger Web. I'm a big fan of Tim's idea of [the Web as a platform](http://www.nla.gov.au/our-publications/staff-papers/from-portal-to-platform). When people
call websites silos I get a little bit riled up because Tim Berners-Lee created 
the Web to break down computing silos at CERN. If a webpage has a URL and
you have a website you can link to that webpage in your HTML. You don't need
to ask permission, or convince anyone. You just do it. We need to think about 
how our collections can become part of the larger Web, and how we 
can take advantage of those links and interactions with people. 

The writer Paul Ford has an awesome blog post from 2011 called 
[The Web is a Customer Service Medium](http://www.ftrain.com/wwic.html). His 
main point is that the Web's success stories are largely 
oriented around the principle he calls Why Wasn't I Consulted (wwic). Paul says:

> "Why wasn't I consulted" ... is the fundamental question of the web. It is the rule from which other rules are derived. Humans have a fundamental need to be consulted, engaged, to exercise their knowledge (and thus power), and no other medium that came before has been able to tap into that as effectively.

People want to use the Web to interact with us. If we fail to give them the 
ability to interact, and don't listen to them, our sites often fail.
It's why your newspaper OCR correction service has been so awesome. People 
want to participate, they want to be part of the work of the NLA. If I squint
a bit WWIC reminds me of Simon's idea of impact. When a Web application stops 
being merely a website and starts to affect people's actual lives.

After attending Wikimania in 2012 I was really struck by how passionate people 
were about Wikipedia, and its mission to spread knowledge. The mission 
of Wikimedia Foundation is:

**slide**

> ... to empower and engage people around the world to collect and develop 
> educational content under a free license or in the public domain, and 
> to disseminate it effectively and globally.

The 1400 people gathered at Wikimania 2012 were there because Wikipedia had
impacted their lives. It's a volunteer organization, and people traveled from
around the globe to be together, to help make Wikipedia work better, to
collaborate and share. It was really impressive.

**slide**

The Galleries, Libraries, Archives and Museums (GLAM) effort at Wikipedia is an
international group of professionals who advocate for cultural heritage
organizations that want to work with Wikipedia. I imagine you know this already
but it was actually started by one of your employees, Liam Wyatt, who was the 
first Wikipedian in Residence at the British Museum. Anyway, several of the
experiments I'm going to show you were inspired by the GLAM movement.

After seeing Simon's talk at NDF I realized that I was subconsciously trying to 
use these toys to explore the impact of our online collections. But I 
went about it in a somewhat sloppy way, not measuring much at all, just groping 
around in the dark without a flashlight. In the future I'm going to keep Simon's
impact model in mind. So as I talk about these experiments I'd like you to 
think of them in terms of how they do or do not measure impact.  How could 
they be improved to measure impact better? I offer them here to you also as 
just a lunch break whimsy.

American Memory
---------------

American Memory is a project that began at the Library of Congress in 1990 
just as the Web was being born. It grew out of an effort to digitize some 
of the unique items in the Library, so that they could be stored on a 
laserdisc, and distributed to libraries, schools and universities for 
students and researchers to use. There were a handful of people that 
were watching the Web come into existence, and they naturally made the 
leap in 1993. The software project is largely in stasis right now, but much of 
the content is being migrated over to a new software platform.

As a prelude to some of this work the Prints and Photographs division at the 
Library of Congress decided to also put some of their photographs on Flickr
as a pilot. Flickr is a place where lots of lovers of photography go, to upload
their own photographs and comment, tag and annotate others. The goal of the
project was to see how people interacted with LC's photographs. 

As part of the project The Chronicling America newspaper project also put 
some of their newspaper pages up there. There was lots of activity. We 
haven't really figured out the right way to pull that activity back 
into our own descriptions of the collections. It did provide a place 
for this interaction to take place, but what actually happened?

Linkypedia
----------

As you can see the American Memory site is somewhat archaic but I had a hunch
that it was still pretty actively used. For the past few years I've been
increasingly interested in Wikipedia: its community and infrastructure. One
day I ran across a special form in Mediawiki that lets you find all the
articles that have an external link to a particular website. I thought it would
be interesting to see how many links there were to American Memory from 
Wikipedia articles. I was so surprised about how many there were I ended up 
creating a toy application called Linkypedia to show folks involved in American
Memory that although their website was kind of antiquated looking, it was
actually used quite a bit by Wikipedians as source material when writing
Wikipedia articles.

I designed Linkypedia so that it would periodically look for new links to your
website, so you could monitor them in your RSS feedreader if you wanted to 
get updates. I really wanted to give cultural heritage organizations like 
the Library of Congress an somewhat realtime idea of how their content was 
being used on Wikipedia and more importantly by who.  At first linkypedia 
allowed anyone to add a website to monitor, but some people added some pretty 
big websites like the New York Times, and the National Institutes of Health, 
which quickly exceeded the capacity of my little webserver. Remember this was 
a toy. I'm currently in the process of thinking about how it could be more 
scalable by running in the Wikipedia Foundation's new labs environment.

* American Memory
* National Digital Newspaper Program
* Trove

I also wanted to create a little webservice that you could give a URL and get
back structured data from Wikipedia, from articles that cite it. What if there
was a little JavaScript widget you could put on your page that would trigger a
lookup on your page, and automatically see context from Wikipedia?

Wikistream
----------

My interest in Wikipedia deepened when I learned that the BBC were using 
Wikipedia content on their website, specifically on their BBC Music pages. Once
when I was in London I happened to see a demo of how an edit to a Wikipedia
article resulted in content being available immediately on the BBC website. I'm
not sure if they are still doing that, but they still provide links to Wikipedia
content on their pages, and actively link to Wikipedia. When I asked some
developers I knew there how they kept theree content up to date I learned 
about these IRC chat rooms that mediawiki uses to announce recent edits. 
The channels are used primarily by automated bots which use the udpate stream 
to prevent spam and vandalism. I happened to log in to the channel for English
Wikipedia and was shocked at how quickly they were updated. I wanted to show
my colleagues in the Library how much Wikipedia was edited. Once upon a time
I used to be a cataloger, and I thought catalogers would be interested to see
the level of engagement and curaton in the Wikipedia community. This is what
gave rise to Wikistream, which is a NodeJS application that listens to all the
IRC channels, and sends the updates to the browser.


Wikipulse
---------

As part of my work on Wikistream I created a little NodeJS library called
wikichanges, which makes it trivial to write JavaScript that listens to the
update stream from all the major language Wikipedias. I thought it would be
interesting to visually see what the edit rates were like relative to each
other. This led to Wikipulse. 

Listen to Wikipedia
-------------------

* created by Stephen LaPorte and Mahmoud Hashemi
* bells are additions, strings subtractions
* green circles anonymous, purple circles are bots, white circles are registered
* [http://listen.hatnote.com/](http://listen.hatnote.com/)

Streams
-------

The web is almost like living organism, or as Wittgenstein might say, a form of
life. As we saw with wikistream and Listen to Wikipedia, nformation is
constantly changing and propagating. We can create streams for our content
too. Consider these:

* paperbot
* lctwee
* trovebot
* British Library's http://mechanicalcurator.tumblr.com/
 
Chroma
------

The National Digital Newspaper Program is a project in the US to digitize the
microfilm of historic newspapers around the country. We've collected a little
over 6 million pages of content so far, and we're still working. 

* Trove's recentSearches (ideas?)
* Newspapers top text correctors (ideas?)

Ici
---

Earlier this year Wikipedia announced that they were enabling an easy image 
upload feature for mobile devices. So if an article lacks an image, and you 
happened to be looking at the article on your mobile device, then you would be 
given an easy upload form to take a picture. I wondered how easy it would be 
to use HTML 5's geolocation features, to create a simple application that 
would show you where you are on a map, and what wikipedia articles are 
relevant for your location, highlighting ones that need an image, and also 
ones that need citations. What would it be like to offer similar interfaces 
for our collections, so that people can easily see what content is relevant 
for their current location?

