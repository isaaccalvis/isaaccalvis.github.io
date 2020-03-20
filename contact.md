---
layout: inner
title: Contact
permalink: /contact/
---

You can contact me directly from LinkedIn, or sending an email (to: <a href="mailto:isaaccalvis@gmail.com">isaaccalvis@gmail.com</a>)

<hr>
{% if site.linkedin_username != '' %}
  <a href="https://www.linkedin.com/in/isaac-calvis-gil-43107a187/"><button class="btn btn-default btn-lg"><i class="fa fa-linkedin fa-lg"></i>LinkedIn</button></a>
{% endif %}

<hr>
<form action="mailto:isaaccalvis@gmail.com" method="post" enctype="text/plain">
Your name:<br>
<input style="border-radius: 8px; border: 2px solid #8a8a8a;" type="text" name="name"><br>
Your email:<br>
<input style="border-radius: 8px; border: 2px solid #8a8a8a;" type="text" name="mail"><br>
Message:<br>
<input style="border-radius: 8px; border: 2px solid #8a8a8a;" type="text" name="comment" size="100"><br><br>
<input style="border-radius: 8px; border: 2px solid #8a8a8a;" type="submit" value="Send">
</form>
