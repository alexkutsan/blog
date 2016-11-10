---
layout: post
title: Try jekyll blog platform.
tags: [jekyll]
---
# Hello World

Hi, I decided to create technical blog, where I will write interesting problems that I am face with. 
I fount out that github allows to host *dynamical* sites! I think that it is rely awesome!
It is rather difficult to create blog on static html pages. 

## Hello Jekyll
There fore good people create site generators that parce some simplified structure and 
creates static web pages. Jekyll is one of them.
It allows create site strucutre using YAML and write blog posts with Markdown

### Jekyll templates
A lot of smart gust created a lot of awesome templates for Jekyll. http://jekyllthemes.org/ 
I like minimalizm, so I forked template from https://github.com/getmicah/blog 
After forking I chenged templte a bit. 
Main changes: 
- tags support 
- blog posts comments with https://disqus.com/ 

### Jekyll test:
#### Common markdown staff
Also I *would* **like** `to test` ```some features``` ~~of markdown~~ in this post :-)
> For exmaple markdown comments

* Markdown
* unordered
* lists

1. Ordered
2. Markdown
3. lists

- [x] Task
- [ ] lists
- [x] with
- [x] Markdown

#### Tables:

First Header | Second Header
------------ | -------------
Content from cell 1 | Content from cell 2
Content in the first column | Content in the second column


#### And image inserting:
![small kkitty](/staff/images.duckduckgo.com.jpe){:class="small"}
![medium kitty](/staff/images.duckduckgo.com.jpe){:class="medium"}
![large kitty](/staff/images.duckduckgo.com.jpe){:class="large"}
![extra large kitty](/staff/images.duckduckgo.com.jpe){:class="extralarge"}


#### Also pice of code :
{% highlight C++ %} 
int main() {
  return 0;
}
{% endhighlight %}



And Task list 
- [x] @mentions, #refs, [links](), **formatting**, and <del>tags</del> supported
- [x] list syntax required (any unordered or ordered list supported)
- [x] this is a complete item
- [ ] this is an incomplete item

End using emoji:
bowtie:
:smile:
:simple_smile:
:laughing:
:blush:
:smiley:
:relaxed:
:smirk:
:heart_eyes:
:kissing_heart:
:kissing_closed_eyes:
:flushed:
:relieved:
:satisfied:
:grin:
:wink:
:stuck_out_tongue_winking_eye:
:stuck_out_tongue_closed_eyes:
:grinning:
:kissing:
:kissing_smiling_eyes:
:stuck_out_tongue:
:sleeping:
:worried:
:frowning:
:anguished:
:open_mouth:
:grimacing:
:confused:
:hushed:
:expressionless:
:unamused:
:sweat_smile:
:sweat:
:disappointed_relieved:
:weary:
:pensive:
:disappointed:
:confounded:
:fearful:
:cold_sweat:
:persevere:
:cry:
:sob:
:joy:
:astonished:
:scream:
:neckbeard:
:tired_face:
:angry:
:rage:
:triumph:
:sleepy:
:yum:
:mask:
:sunglasses:
:dizzy_face:
:imp:
:smiling_imp:
:neutral_face:
:no_mouth:
:innocent:
:alien:
:yellow_heart:
:blue_heart:
:purple_heart:
:heart:
:green_heart:
:broken_heart:
:heartbeat:
:heartpulse:
:two_hearts:
:revolving_hearts:
:cupid:
:sparkling_heart:
:sparkles:
:star:
:star2:
:dizzy:
:boom:
:collision:
:anger:
:exclamation:
:question:
:grey_exclamation:
:grey_question:
:zzz:
:dash:
:sweat_drops:
:notes:
:musical_note:
:fire:
:hankey:
:poop:
:shit:
:+1:
:thumbsup:
:-1:
:thumbsdown:
:ok_hand:
:punch:
:facepunch:
:fist:
:v:
:wave:
:hand:
:raised_hand:
:open_hands:
:point_up:
:point_down:
:point_left:
:point_right:
:raised_hands:
:pray:
:point_up_2:
:clap:
:muscle:
:metal:
:fu:
:runner:
:running:
:couple:
:family:
:two_men_holding_hands:
:two_women_holding_hands:
:dancer:
:dancers:
:ok_woman:
:no_good:
:information_desk_person:
:raising_hand:
:bride_with_veil:
:person_with_pouting_face:
:person_frowning:
:bow:
:couplekiss:
:couple_with_heart:
:massage:
:haircut:
:nail_care:
:boy:
:girl:
:woman:
:man:
:baby:
:older_woman:
:older_man:
:person_with_blond_hair:
:man_with_gua_pi_mao:
:man_with_turban:
:construction_worker:
:cop:
:angel:
:princess:
:smiley_cat:
:smile_cat:
:heart_eyes_cat:
:kissing_cat:
:smirk_cat:
:scream_cat:
:crying_cat_face:
:joy_cat:
:pouting_cat:
:japanese_ogre:
:japanese_goblin:
:see_no_evil:
:hear_no_evil:
:speak_no_evil:
:guardsman:
:skull:
:feet:
:lips:
:kiss:
:droplet:
:ear:
:eyes:
:nose:
:tongue:
:love_letter:
:bust_in_silhouette:
:busts_in_silhouette:
:speech_balloon:
:thought_balloon:
:feelsgood:
:finnadie:
:goberserk:
:godmode:
:hurtrealbad:
:rage1:
:rage2:
:rage3:
:rage4:
:suspect:
:trollface:
