---
layout: post
title:  "Happy Engineers Day 2018"
date:   2018-09-15
desc: "A geeky and cheesy Engineer's day special code snippet :p"
keywords: "JavaScript,SweetAlert,HTML,website,blog,easy,code,snippets,engieers day, engineer's day, engineersday, engineers day 2018, engineers day 2018 wish"
categories: [Coding]
tags: [engineers day, javascript]
icon: icon-html
---

Engineering invovles just the right mix of left and right brain function and Engieeers are the real rockstar who sacrifice their own sleep and health to make our lives better and easier. 

Here's a small snippet I made to wish you all amazing software engineers out there a very happy engineers day. You guys rock. Keep creating cool stuff! 😊 

```

<script src="https://unpkg.com/sweetalert/dist/sweetalert.min.js"></script>
<script>
	var u = 'Software Engineer';
	swal("What is your profession ?", {
	  content: "input",
	})
	.then((value) => {
	  var urProfession = value;
	  var today = new Date();
	  var dd = today.getDate();
	  var mm = today.getMonth()+1;
	  var today = dd + '/' + mm;
	  var engineersDay = '15/9';
	  var isUCool = urProfession.indexOf('engineer');
	  	if(isUCool>=0) {
	  		if(today == engineersDay ) {
	  			swal("Happy Engineers Day!", "You Rock! Keep being awesometacular :D !", "warning");
	  		} else {
	  			swal(urProfession + " is the best proffession! :) ", "You Rock! Keep being awesome :D !", "info");
	  		}
	  	}
	  	else {
	  		swal(urProfession+" is cool!", "...but engineering is even cooler :P !");
	  	}
	});	
</script>

```

