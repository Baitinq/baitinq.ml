---
title: "OSXIV"
date: 2022-07-31T17:36:24+02:00
notshowthedate: true
draft: false
---


<div id="fetched-markdown"></div>

<script src="https://cdn.jsdelivr.net/npm/showdown@1.9.0/dist/showdown.min.js" type="text/javascript"></script>

<script>

fetch("https://raw.githubusercontent.com/Baitinq/OSXIV/master/README.md").then((response) => response.text()).then((data) => {
	console.log(data);
	const converter = new showdown.Converter();
	const html      = converter.makeHtml(data);
	document.getElementById('fetched-markdown').innerHTML = html;
});
</script>

-----

This information was fetched from [OSXIV's](https://github.com/Baitinq/OSXIV) [README]("https://raw.githubusercontent.com/Baitinq/OSXIV/master/README.md").
