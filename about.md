---
layout: page
title: About 
permalink: /about/
---

I am Norzin :) I am a cool person who is very cool. This is my website. 

<div id="guestbook-entries"></div>
<script>
  fetch('https://api.github.com/repos/your-username/your-repo/issues')
    .then(response => response.json())
    .then(data => {
      const entries = data.map(issue => `<p><strong>${issue.title}</strong>: ${issue.body}</p>`).join('');
      document.getElementById('guestbook-entries').innerHTML = entries;
    });
</script>

         

### More Information

meowmeowmeowmeowmeow 

### please hesitate to contact me

worms1nbrainn@gmail.com 
