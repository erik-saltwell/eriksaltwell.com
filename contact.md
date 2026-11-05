---
layout: page
title: Contact me
share-description: Email and social links for Erik Saltwell.
permalink: /contact/
---

{% assign contacts = site["social-network-links"] %}

Want to ask about something I've made, talk about work, or just say hello?

- **Email:** [{{ contacts.email }}](mailto:{{ contacts.email }})
- **LinkedIn:** [{{ contacts.linkedin }}](https://www.linkedin.com/in/{{ contacts.linkedin }})

You can also find me here:

- [GitHub](https://github.com/{{ contacts.github }}) — code and projects
- [itch.io](https://{{ contacts.itchio }}.itch.io/) — games and tabletop projects
- [Bluesky](https://bsky.app/profile/{{ contacts.bluesky }})
- [X / Twitter](https://twitter.com/{{ contacts.twitter }})

To follow new posts on this site, subscribe to the [RSS feed]({{ '/feed.xml' | relative_url }}).
