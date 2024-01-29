---
layout: default
title: Homepage
---

### About Me

Greetings, and thanks for visiting. I'm a full-time engineer and hobbyist developer based in the United States, and I share my projects and various other online things under the aliases Priere and shiyouganai. I love virtual reality, music, and crossword puzzles. You can find some of my latest fixations below!

---

### Projects
{% for project in site.projects %}
#### [{{ project.title }}]({{ project.exturl }})
{: #project-title}
#### {{ project.year }}
{: #project-date}
<div class="clearhack"></div>
[![{{ project.title }}]({{ project.banner }})]({{ project.exturl }}){: #project-image}  
{{ project.description }}
{% endfor %}

---

### Miscellany

#### Mascot Character/Persona

![Priere](/assets/priere_kemono_wave_800x1700.png)
{: .left-content}

**Priere** ([Reference Gallery](/gallery/priere-reference))  
My current mascot character/persona represents me all over the social internet, including in VRChat. He is a Kemono style fox; I really like that genre of artwork.

<div class="clearhack"></div>

#### Other OCs

![Chloe](/assets/chloe_punqakes_chibi_740x820.png)
{: .right-content}

**Chloe** ([Reference](/assets/chloe_main_reference_2200x1600.png))  
An energetic cat girl, from which my persona and VR avatars derive their color scheme.
{: .right-content}

![Sophia](/assets/sophia_punqakes_chibi_740x820.png)
{: .left-content}

**Sophia** ([Reference](/assets/sophia_main_reference_4000x3942.png))  
A bookish bat girl who loves sweaters.
{: .left-content}

<div class="clearhack"></div>

#### Public Accounts

* [Twitter/X](https://x.com/shiyouganai)  
  This is my main public social media account.  
  * Advance warning: it's general purpose, has lots of non-programming content, and I don't guarantee it's worksafe.
  * If you need to get in contact with me, this is a good way to do it.  
  * My VRChat ID is in my bio. I love social VR! Feel free to chat with me about it or ask to join me in game. However, please do not send unsolicited friend requests without first introducing yourself.
* [Twitch](https://www.twitch.tv/priere__)  
  This is where I (rarely) stream.
* [FFXIV Character Profile](https://na.finalfantasyxiv.com/lodestone/character/10232780/)  
  [FFLogs Profile](https://www.fflogs.com/character/na/cactuar/priere%20d'enpa)  
  One of my hobbies is playing MMORPGs, and I've been an active FFXIV player for quite a few years. I'm linking my character information here because I'm always willing to say hello to a fellow player.
