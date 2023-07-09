---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
---

*These pages represent my personal views and not the views of my employer.*

posts:

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>

[about](/about/)

<div width=825px height=400px style="overflow: hidden">
    <iframe src="https://gateway.fxhash2.xyz/ipfs/QmTTQySXTFFHph2LE3n5PhSpW7T31YzRQ7vsZhHs3taxU8/?fxhash=ooJt6rBXDufkfy8WEaaB5f29K2TK4TxddKpFxjmzraH5YKx9iUg&fxminter=tz1gyRDex98FvidbimVQFiNYmd7LdnVbmRyr" name="bitrpy by formerlyknownas" width=825px height=400px style="border:none; position: relative; top: -200px">
    </iframe>
</div>