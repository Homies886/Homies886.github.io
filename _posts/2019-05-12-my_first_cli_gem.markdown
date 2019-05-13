---
layout: post
title:      "My First CLI Gem"
date:       2019-05-13 01:10:39 +0000
permalink:  my_first_cli_gem
---


I'm new to blogging in general and also new to coding. The purpose of this blog is to describe my project and how I went about doing it.

I would definitely classify myself as a gamer. It is a hobby. It is a passion. It is a way of life. Naturally, I decided to make my CLI based off of a video game. I absolutely love the Pokemon series of games, so I started searching for websites I could use for the project. I found that one I've used personally in the passed was https://pokemondb.net/ which is useful in many ways with the amount of information it provides. My first step was diving in and seeing if I could scrape the data I needed and how I would be able to use that data. This was probably the longest step for me as I can't tell you how many times I tested scraping the sites to try and get the exact data I needed. Once I was comfortable with grabbing the data I needed I moved on to my next step.

My next step was learning/figuring out how to create a gem! I understand that for most, that probably was step 1, but I mistakenly just glanced over the instructions for the project and then dove in as I was excited to get started. Thanks to the instructional video provided, it only took me about 3-5 attempts to create the gem before I understood what I was doing and what files were being created. I also looked at the example project as a reference to make sure I had everything I needed. I know this is slightly off topic, but I'm really not a fan of the Learn IDE 3. That sucker disconnects randomly and you lose everything you were working on. Needless to say, I was adding, committing, and pushing to git often. Now that my gem was set up, I moved on to the next step of creating my classes.

At first, I created a scraper class, a CLI class, and a pokedex class. The class names basically describe what each class is supposed to do, however I struggled with the pokedex class as I was trying to do too much in the one class. It became clear to me that I needed to create another class called pokemon. This way I could separate the data I was grabbing into more defined classes. This really helped me to understand my own project even more as I was able to logically think about what the pokedex class did as a single object and what the pokemon class did as a single object. Everything started to flow more easily once I did that. Since I had already tested the scraping a bunch, the scraper class was easier for me to code. The CLI class was a little tricky as I had to create some error handling or "dummy proofing". If I'm honest, I could have probably written the CLI class a little better/cleaner, but my deadline was approaching fast and I was mentally spent.

My last step was testing. In hindsight I probably should have tested throughout, but I was actually pretty proud of the way my gem was working by the time I actually started testing. There were some errors I was stumped on, but after some digging and trying out 50 or so different fixes, I was finally able to use my gem without any errors.

This project definitely put me to the test. There were times I though I wasn't going to be able to finish in time, if at all. I'm proud of myself for sticking with it and pushing through. I'm also glad to know that I did in fact learn something over the last few months and that I was able to put that knowledge to work.

I probably should have added this info somewhere earlier, but better late than never. My gem gives you a list of pokedexes and asks the user to select one. Based off of the users selection, it gives them a list of the pokemon that are included in that pokedex. The user is then able to select a pokemon and get a small description of that pokemon.
