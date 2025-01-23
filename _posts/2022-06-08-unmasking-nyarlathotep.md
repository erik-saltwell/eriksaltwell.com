---
layout: post
title: Unmasking Nyarlathotep Clue Search App
subtitle: A pepe silva clueboard for our Masks campaign
tags: [rpg, website]
author: Erik Saltwell
---
My friend and extraordinary GM, Jason Beaumont is running Call of Cthulhu's Masks of Nyarlathotep for me and our friends!   This is a huge, world-spanning campaign and Jason sprung for the immersive physical handouts.  In order to help the party keep track of all the clues, I built a web app on top of Azure Cognitive Search that processes photographs of all the clues and makes all the text searchable.  The app is called Unmasking Nyarlathotep.
![Eye of Agamotto](/assets/img/unmasking-home.jpg)
{{< image src="postimg/unmasking-home.jpg" alt="Home page of the Unmasking Nyarlathotep web app" class="left">}}

From here you can enter a term (like 'Carlyle') and it will bring up all the clues that contain the text (with highlighting of the term!).
![screenshot](/assets/img/unmasking-clues.jpg)
{{< image src="postimg/unmasking-clues.jpg" alt="Clues page of the Unmasking Nyarlathotep web app" class="left">}}

If you click on a clue, it zooms in so you can read the details of the clue.
![screenshot](/assets/img/unmasking-lightbox.jpg)
{{< image src="postimg/unmasking-lightbox.jpg" alt="Clues page of the Unmasking Nyarlathotep web app" class="left">}}

The map page shows you any locations mentioned in your currently selected clues.
![screenshot](/assets/img/unmasking-map.jpg)
{{< image src="postimg/unmasking-map.jpg" alt="Map page of the Unmasking Nyarlathotep web app" class="left">}}

The timeline page takes any dates referenced and puts them in chronological order.
![screenshot](/assets/img/unmasking-timeline.jpg)
{{< image src="postimg/unmasking-timeline.jpg" alt="Timeline page of the Unmasking Nyarlathotep web app" class="left">}}

The people page shows you how people mentioned in the clues are connected.  A connection means they are both referenced in at least one clue together.
![screenshot](/assets/img/unmasking-people.jpg)
{{< image src="postimg/unmasking-people.jpg" alt="People page of the Unmasking Nyarlathotep web app" class="left">}}
