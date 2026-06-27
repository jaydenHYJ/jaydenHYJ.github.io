---
layout: archive
title: "Contact"
permalink: /contact/
author_profile: true
---

<style>
:root { --fd-blue: #0E5AA7; }
</style>

<div style="background:#ffffff; border:1px solid #e5e5e5; border-radius:12px; padding:28px 32px; margin:20px 0; box-shadow:0 2px 10px rgba(0,0,0,0.06);">
<p style="font-size:1rem; color:#555; margin-top:0; margin-bottom:20px;">
Feel free to send me a message. Filling out this form will open your email client with the message pre-filled. You can also reach me directly at <a href="mailto:yjhan@fudan.edu.cn">yjhan@fudan.edu.cn</a>.
</p>
<form onsubmit="sendContactEmail(event)" style="display:flex; flex-direction:column; gap:14px;">
  <div>
    <label for="contact-name" style="display:block; font-size:0.9rem; color:#555; margin-bottom:4px; font-weight:500;">Name</label>
    <input type="text" id="contact-name" required style="width:100%; padding:9px 12px; font-size:0.95rem; border:1px solid #ddd; border-radius:6px; box-sizing:border-box; font-family:inherit;" />
  </div>
  <div>
    <label for="contact-email" style="display:block; font-size:0.9rem; color:#555; margin-bottom:4px; font-weight:500;">Your Email</label>
    <input type="email" id="contact-email" required style="width:100%; padding:9px 12px; font-size:0.95rem; border:1px solid #ddd; border-radius:6px; box-sizing:border-box; font-family:inherit;" />
  </div>
  <div>
    <label for="contact-subject" style="display:block; font-size:0.9rem; color:#555; margin-bottom:4px; font-weight:500;">Subject</label>
    <input type="text" id="contact-subject" placeholder="(optional)" style="width:100%; padding:9px 12px; font-size:0.95rem; border:1px solid #ddd; border-radius:6px; box-sizing:border-box; font-family:inherit;" />
  </div>
  <div>
    <label for="contact-message" style="display:block; font-size:0.9rem; color:#555; margin-bottom:4px; font-weight:500;">Message</label>
    <textarea id="contact-message" rows="5" required style="width:100%; padding:9px 12px; font-size:0.95rem; border:1px solid #ddd; border-radius:6px; box-sizing:border-box; font-family:inherit; resize:vertical;"></textarea>
  </div>
  <button type="submit" style="background:var(--fd-blue); color:#ffffff; border:none; padding:11px 24px; border-radius:6px; font-size:1rem; font-weight:600; cursor:pointer; align-self:flex-start;">✉️ Send</button>
</form>
</div>
<script>
function sendContactEmail(event) {
  event.preventDefault();
  var name = document.getElementById('contact-name').value;
  var email = document.getElementById('contact-email').value;
  var subject = document.getElementById('contact-subject').value || 'Message from your website';
  var message = document.getElementById('contact-message').value;
  var body = 'From: ' + name + ' (' + email + ')\r\n\r\n' + message;
  var mailto = 'mailto:yjhan@fudan.edu.cn'
             + '?subject=' + encodeURIComponent(subject)
             + '&body=' + encodeURIComponent(body);
  window.location.href = mailto;
}
</script>
