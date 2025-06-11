---
layout: single
title: "Contact"
permalink: /contact/
author_profile: false
classes: wide
---

## 🤝 Let's Connect

I’m currently available for:

- Freelance Projects  
- Contract Work  
- Consulting  
- Remote Opportunities

Let’s discuss how I can contribute to your next project!

---

## 📩 Send Me a Message

<form id="contact-form" action="https://formspree.io/f/mvgraovk" method="POST">
  <label for="name"><strong>Name *</strong></label><br>
  <input type="text" id="name" name="name" required style="width: 100%; padding: 8px;"><br><br>

  <label for="email"><strong>Email *</strong></label><br>
  <input type="email" id="email" name="_replyto" required style="width: 100%; padding: 8px;"><br><br>

  <label for="subject"><strong>Subject</strong></label><br>
  <input type="text" id="subject" name="subject" style="width: 100%; padding: 8px;"><br><br>

  <label for="message"><strong>Message *</strong></label><br>
  <textarea id="message" name="message" rows="6" required style="width: 100%; padding: 8px;"></textarea><br><br>

  <button type="submit" style="padding: 10px 20px; background-color: #007acc; color: white; border: none; cursor: pointer;">Send Message</button>
</form>

<script>
  const form = document.getElementById("contact-form");
  form.addEventListener("submit", async function (e) {
    e.preventDefault();
    const formData = new FormData(form);
    const response = await fetch(form.action, {
      method: form.method,
      body: formData,
      headers: {
        'Accept': 'application/json'
      }
    });

    if (response.ok) {
      form.reset();
      alert("Message sent successfully!");
    } else {
      alert("Something went wrong. Please try again.");
    }
  });
</script>
