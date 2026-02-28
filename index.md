---
layout: default
title: Vessel
---

# Welcome to the Vessel project. This site is currently being configured and deployed.

## What this project will include
- Documentation
- Feature roadmap
- Release notes
  
## Explore the Ecosystem
- **[Darkness](https://medium.com/@ending_glosses.26)** - experiments + dashboards
- **[Wordpress](https://momentismedical.dev)** - longform writing + updates
- **[Medium](https://medium.com/@Snapback17)** - secondary blog
- - **[Gravatar](https://gravatar.com/momentismedical)**

## Socials
- **[Facebook](https://www.facebook.com/profile.php?id=61582103756491)**
- **[Instagram](https://www.instagram.com/the_moment_is_medical25/)**
- **[Threads](https://www.threads.com/@the_moment_is_medical25)**
- **[X](x.com/strait_chlorine)** 

## Latest Updates
Content will appear here as the site deploys.
## All Posts (Automatic List)
<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
