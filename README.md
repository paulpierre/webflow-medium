```
█░░░█ █▀▀ █▀▀▄ █▀▀ █░░ █▀▀█ █░░░█ ░░ █▀▄▀█ █▀▀ █▀▀▄ ░▀░ █░░█ █▀▄▀█ ░ ░░▀ █▀▀ 
█▄█▄█ █▀▀ █▀▀▄ █▀▀ █░░ █░░█ █▄█▄█ ▀▀ █░▀░█ █▀▀ █░░█ ▀█▀ █░░█ █░▀░█ ▄ ░░█ ▀▀█ 
░▀░▀░ ▀▀▀ ▀▀▀░ ▀░░ ▀▀▀ ▀▀▀▀ ░▀░▀░ ░░ ▀░░░▀ ▀▀▀ ▀▀▀░ ▀▀▀ ░▀▀▀ ▀░░░▀ █ █▄█ ▀▀▀
```

### webflow-medium.js - Dynamically embed medium articles in Webflow 👍

---

## About

webflow-medium is a script you can embed onto your hosted website like Webflow, Shopify, Square Space that allows you to directly inject your article meta data directly onto the page.

by [@paulpierre](https://www.twitter.com/paulpierre), a blockchain developer @ [https://www.conductiveresearch.com](https://www.conductiveresearch.com)

join us we're hiring 🧑‍🔬🏴‍☠️👩‍🔬

## Features
* 🏴‍☠️ Get around Medium.com from accessing your own content! Embed your articles
* 🔒 Preserves the style of your theme, just swaps content
* ⚙️ Fill in CSS query selectors, and the rest is done
* 👁️ Calculates amount of minutes it takes to read!
* ⚠️ Set the maximum length of the title and description
* 🖼️ Set a default image if no thumbnail is found


## Metadata
* Article title
* Article description / preview
* Article # of minutes to read
* Article link

## Get started

1. Open webflow-medium.js and edit the section beneath `// Configuration values`
2. Set your Medium.com users name under `USERNAME`
3. Makes sure you setup a dummy layout on Webflow for the medium articles
4. Configure your CSS selectors, embed script in Webflow and rock and roll!

## How it works

Currently Medium does not really provide get APIs for your content or embed your medium articles in any meaningful way. Currently embedding results in styling the embed in Medium's style guide. This is silly, that's why I'm here.

* Every medium has an RSS feed accessible via `https://medium.com/feed/@yourusername`
* I simply pass this to a free RSS to JSON service
* Loop and inject through the selectors .. very basic 💩 


## TODO:
* Make certain Medium metadata optional
* Limit description by word length rather than character length
* Make images a >1 selector rather than individual. This was done bc of the particular site I was working with. Too lazy.
* Create a function to directly parse the XHTML rather than relying on rss2json.com API

If you want additional features, find bugs, just submit an issue



Interested in blockchain and dApp development. Were hiring and looking for pirates 🏴‍☠️, [https://www.conductiveresearch.com](https://www.conductiveresearch.com)

Give this a ⭐ above ☝️ and me a follow on [Twitter]](https://www.twitter.com/paulpierre) if you liked this 👍
