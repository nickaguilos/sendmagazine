---
layout: page
title: Contact Send
---

<form action="https://formspree.io/hey@sendmagazine.com"
      method="POST">
      <h3 class="section-heading">Mail us, maybe?</h3>
      <p>
      	Do you have questions or stories you want us to publish? Send us an email so we can take a look
      </p>
    <fieldset>
    	<label for="name">Your Name</label>
    	<input type="text" name="name">
	</fieldset>

    <fieldset>
    	<label for="_replyto">Email</label>
    	<input type="email" name="_replyto">
	</fieldset>

    <fieldset>
    	<label for="message">Optional Message</label>
    	<textarea name="message" id="" cols="30" rows="2"></textarea>
    </fieldset>
    
    <button type="submit">Send</button>
</form>