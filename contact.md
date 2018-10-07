---
layout: page
title: Contact
---

<p>你好！歡迎訪問 <a href="https://github.com/genghis-bai" target="_blank" style="color:#663399;">github</a> 與我互動！或者使用以下表單給我發郵件吧！</p>

<form class="wj-contact" action="https://formspree.io/winwinsfu@gmail.com" method="POST">
    <input type="text" name="name" placeholder="Your Name">
    <input type="email" name="email" required placeholder="Email Address">
    <textarea type="text" name="content" rows="10" placeholder="Message"></textarea>
    <input type="hidden" name="_next" value="/">
    <input type="hidden" name="_subject" value="New Contact Form Submission">
    <input type="text" name="_gotcha" style="display:none">
    <input type="submit" value="Submit">
</form>

<style>
a:focus,
button:focus,
input:focus,
textarea:focus {
outline: none;
}

form.wj-contact input[type="text"], input[type="email"], form.wj-contact textarea[type="text"] {
    width: 100%;
    vertical-align: middle;
    margin-top: 0.25em;
    margin-bottom: 0.5em;
    padding: 0.75em;
    font-family: monospace, sans-serif;
    font-weight: lighter;
    border-style: solid;
    border-color: #444;
    outline-color: #663399;
    border-width: 1px;
    border-radius: 3px;
    transition: box-shadow .2s ease;
}
form.wj-contact input[type="submit"] {
    outline: none;
    color: white;
    background-color: #663399;
    border-radius: 3px;
    padding: 1em 3em;
    margin: 0.25em 0 2em 0;
    border: 1px solid transparent;
		height: auto;
		cursor: pointer;
}
</style>