---
# Fill-in Speaker1, Speaker2, & Speaker3 info below.
# Add tag(s) related to your presentation. Use lowercase tags. Also add "Your Name" as a tag.
title: "Web & Application Professionals Meetup – Dec 1"
tags: ["Katie Phillips"]
meeting_time: "6:30-9p"
meeting_start: "18:30"
venue: "GJ" # WELABS || GJ
venue_image: "/images/GJ-presentation.jpeg"
rsvp: "http://www.meetup.com/Uncoded/events/226862884/" # "http://www.meetup.com/Uncoded/events/225429587/"
categories: meetup
layout: post
published: true
speaker1:
  name: "Katie Phillips"                 # Speaker Full Name
  company: "Katie Phillips Design"       # Speakers Employer
  presentation_type: "PRESENTATION"      # PRESENTATION || SHOWCASE || DEMO || PANEL
  bio_img_path: "/images/people/katie-phillips.jpg"  
  bio_desc: "Katie Phillips is a locally-based graphic designer with over 15 years experience in web and print. She has worked with FOX on American Idol Season 8 and 9's website design, was art director for Edge Music Network's website, and has worked for Fortune 500 companies such as Macy's, Target, Bloomingdales, Wal-Mart, Sony, Warner Bros. She's also worked with celebrities such as rapper Too Short, singer-songwriter Leonard Cohen, and rock idol Steven Tyler of Aerosmith. She graduated Otis College of Art and Design in 2000 with a BFA in Illustration and began her own design company, Katie Phillips Design, in 2012. Katie is passionate about design and details and loves design make-overs. When she's not at the computer you can find her hanging out with her art collective Squeeze, painting, hiking, and networking!"           # Speaker Biography. markdown ok.
  presentation_title: "Why You Should Move That Button 3 Pixels To The Left" # Catchy Title of Presentation.
  presentation_desc: "Why is it so important to fix small design bugs? Will it really improve the product that much? YES. A trust-worthy website is both functional and shows aligned elements along with elegant interactions. Learn more about how you can work with your designer to create gorgeous, functional websites with designer Katie Phillips."  # Full Description of talk.  markdown ok.
  twt_name: ""           # Twitter Handle, sans @
speaker2:
  name: "Roger Howard"               # Speaker Full Name
  twt_name: "rogerhoward"           # Twitter Handle, sans @
  company: "CritiqueIT"            # Speakers Employer
  bio_desc: "Roger Howard is an accomplished technology architect and software developer with a focus on  the intersection of creative media and technology. After more than fifteen years in senior roles at iconic organizations such as The Getty, Blizzard, and Playboy, Roger traded in the comfortable confines of corporate culture to follow his passions and need for self-determination.

  He currently serves as the CTO for Critique­it, a hometown startup, and provides strategic technology consulting and software development services to non­profits such as museums and charities. Roger has too many side projects and interests, and not enough hours in the day."           # Speaker Biography. markdown ok.
  bio_img_path: "/images/people/roger-howard.jpg"       # Path to image, ex: '/images/people/foobar.jpg'
  presentation_type: "PRESENTATION"  # PRESENTATION || SHOWCASE || DEMO || PANEL
  presentation_title: "AWS + DEVOPS (details forthcoming)" # Catchy Title of Presentation.
  presentation_desc: ""  # Full Description of talk.  markdown ok.
speaker3:
  name: "Steve Kochan"               # Speaker Full Name
  twt_name: "COMFREIGHT"           # Twitter Handle, sans @
  company: "Gunn|Jerkens"            # Speakers Employer
  presentation_type: "PRESENTATION"  # PRESENTATION || SHOWCASE || DEMO || PANEL
  bio_desc: "Steve Kochan is the Project Manager at Gunn Jerkens, Founder and CEO of ComFreight.com (a bootstrapped and recently profitable SaaS startup from Long Beach) and former Executive Director of LB Tech."
  bio_img_path: "https://media.licdn.com/mpr/mpr/shrinknp_200_200/AAEAAQAAAAAAAAPHAAAAJGUyMTBmNzNhLTI5NjgtNDVjZC04NmVjLThmN2NhODRiZDcyNQ.jpg"
  presentation_title: "Fail Less, Validate Faster"
  presentation_desc: "Explanation of quicks ways to validate a business or application idea using quick to deploy forms or landing pages and a small paid advertising budget using PPC to find out if that idea is really worth doing. Find out if your idea has actual interest and initial traction and quickly ascertain your initial cost per acquisition before building the entire product. Intro to product marketing research."
sponsors:
  food:
    name: ""
    logo: ""
    twitter: ""
    desc: ""
    extra: ""
  prize:
    pearson:
      name: ""
      image: ""
      logo: ""
      twitter: ""
      desc: ""
      extra: ""
---

{% if page.venue_image != "" %}<img src="{{ base.url }}{{ page.venue_image }}" alt="monthly promotional picture">{% endif %}

## TALKS THIS MONTH  
The _Long Beach Web & App Professionals_ ([#WAPRO](https://twitter.com/intent/tweet?text=I%27m%20excited%20for%20the%20%23WAPRO%20meetup%20this%20month!%20meetup.com%2Funcoded%2Fevents%2F%20%40uncodedlb%20%23uncoded)) group meets monthly to share and learn about the technology that ignites our imagination, builds our skill-set, expands our network, and grows community!

{% if page.speaker1.presentation_title != ""  %}- {{ page.speaker1.name }} ([@{{ page.speaker1.twt_name }}](https://twitter.com/{{ page.speaker1.twt_name }})) – {{ page.speaker1.presentation_title }}  {% endif %}
{% if page.speaker2.presentation_title != ""  %}- {{ page.speaker2.name }} ([@{{ page.speaker2.twt_name }}](https://twitter.com/{{ page.speaker2.twt_name }})) – {{ page.speaker2.presentation_title }}  {% endif %}
{% if page.speaker3.presentation_title != ""  %}- {{ page.speaker3.name }} ([@{{ page.speaker3.twt_name }}]({{ site.base.twitter }}{{ page.speaker3.twt_name }})) – {{ page.speaker3.presentation_title }}  {% endif %}
- [PLEASE R.S.V.P.]({{ page.rsvp }})

<!--break-->
##VALUE

Tech moves too fast to keep up on everything yourself.  There's always someone faster, better, or smarter than you.  Come meet them, connect, and lean on community.  If you're a local business or agency, join us and encourage staff to come.  It's a great way to expand your network of folks active and connected, which leads to both new business and potential new recruits.  Everyone wins!


##TOPICS

The Pros that have worked on/for projects such as Spacex, Riot Games, X-prize, Adobe, Toyota Motor Sports, VMWare, UCLA, CSULB, AARP, and more ... have shared amazing talks this year on tech and projects such as [Bootstrap](http://getbootstrap.com/), [Bower](http://bower.io), [Browserfy](http://browserify.org/), [Headless Drupal](https://github.com/davidhwang/horseman), [iOS Swift](https://developer.apple.com/swift/), [Jekyll](http://jekyllrb.com), [Meteor](https://www.meteor.com/), [Node.js](https://iojs.org/en/), [SASS](http://sass-lang.com/), [Sculpin](http://sculpin.io), [Zapier](http://zapier.com) and more.

Every month we come together to:

* Demo technologies we use, especially those driving the convergence of websites and mobile apps
* Showcase our projects built with cool tech
* Share industry "best practices"
* Newcomer Q&A's
* Network, get to know each other, and otherwise have fun

We have a preference for open-source software, especially server-side.  This year we have meetups focused on the life-cycle and technologies related to website and application development.  We will especially try to delve into situations where mobile and web technologies converge.  The meeting topics we cover will vary monthly and will be tailored to, and by, our community.  Want to see something in particual?  Let us know by tweeting using the hash #WAPRO.  

**Future meetup dates:**  10/6  ⛅  11/3  ⛈  12/1  ☔  1/5  ☃

If you have interest or work in Web or Application Development, add our meetup to your calendar now and join us! Our meetups are FREE and open to [EVERYONE](https://github.com/uncodedlb/uncoded-policies).


{% include venue.md %}


### DETAILS  
{% if page.speaker1.name != "" %}
**{{ page.speaker1.presentation_type | uppercase }}**  
{{ page.speaker1.presentation_title | uppercase }}  

{{ page.speaker1.presentation_desc | markdownify }}  

> ### {{ page.speaker1.name | markdownify }}{% if page.speaker1.company %}
> {{ page.speaker1.company }}{% endif %}  ([@{{ page.speaker1.twt_name }}](https://twitter.com/{{ page.speaker1.twt_name }}))  
> <img src="{{ site.baseurl }}{{ page.speaker1.bio_img_path }}" alt="headshot" class="headshot">
> {{ page.speaker1.bio_desc | markdownify }}  
{% endif %}
{% if page.speaker2.name != ""  %}
**{{ page.speaker2.presentation_type | uppercase }}**  
{{ page.speaker2.presentation_title | uppercase }}

{{ page.speaker2.presentation_desc | markdownify }}  

> ### {{ page.speaker2.name | markdownify }}{% if page.speaker2.company %}
> {{ page.speaker2.company }}{% endif %}  ([@{{ page.speaker2.twt_name }}](https://twitter.com/{{ page.speaker2.twt_name }}))  
> <img src="{{ site.baseurl }}{{ page.speaker2.bio_img_path }}" alt="headshot" class="headshot">
> {{ page.speaker2.bio_desc | markdownify }}  
{% endif %}
{% if page.speaker3.name != ""  %}
**{{ page.speaker3.presentation_type | uppercase }}**  
{{ page.speaker3.presentation_title | uppercase }}

{{ page.speaker3.presentation_desc | markdownify }}  

> ### {{ page.speaker3.name | markdownify }}{% if page.speaker3.company %}
> {{ page.speaker3.company }}{% endif %}  ([@{{ page.speaker3.twt_name }}](https://twitter.com/{{ page.speaker3.twt_name }}))  
> <img src="{{ site.baseurl }}{{ page.speaker3.bio_img_path }}" alt="headshot" class="headshot">
> {{ page.speaker3.bio_desc | markdownify }}  
{% endif %}



## SPONSORS

Our sponsors help make our meetups awesome! They feed us, provide a place to gather, share, & learn from eachother, and some even give us cool things to giveaway!  Take a moment to thank them, click their logo to visit their twitter/facebook account... and thank them publicly.  *(Please, use hash __#WAPRO__)*

{% if page.sponsors.food.name != "" %}
### FOOD & BEVERAGES
{% endif %}
{% if page.sponsors.food.logo != "" %}<a href="{{ site.base.twitter }}{{ page.sponsors.food.twitter }}" target="_blank"><img class="logo" src='{{ page.sponsors.food.logo }}' alt='{{ page.sponsors.food.name }}'></a>
<p>Come hungry & thirsty! This month food and beverage will be graciously provided by <a href="{{ site.base.twitter }}{{ page.sponsors.food.twitter }}" target="_blank">{{ page.sponsors.food.name }}</a>.  {{ page.sponsors.food.desc }}</p>{% endif %}
{% if page.sponsors.food.extra %}<p>{{ page.sponsors.food.extra }}</p>{% endif %}
