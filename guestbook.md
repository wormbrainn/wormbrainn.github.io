---
layout: page
title: Guestbook
permalink: /guestbook/
---

## Leave a Message

<form action="https://your-netlify-form-endpoint" method="POST">
    <label for="name">Name:</label>
    <input type="text" id="name" name="name" required>
    <br>
    <label for="message">Message:</label>
    <textarea id="message" name="message" rows="4" required></textarea>
    <br>
    <input type="submit" value="Submit">
</form>
