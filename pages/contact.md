---
layout: page
title: 'Contact'
date: '2020-04-13'
author: bob-spiegelman
permalink: /contact/
redirect_from: /contact.html
---
## Contact Sullivan/Clinton

<form id="contactform" action="#" method="post"> <!--UPDATE ACTION-->
<p><label for="Subject">Message Type:</label><br />
<select name="Subject" id="Subject">
<option selected="selected">Book a Lecture</option>
<option>Info</option>
<option>Inquiry</option>
<option>Proposal</option>
</select></p>
<p><label for="name">Name:</label><br /> <input type="text" name="Name" id="name" size="30" /><br /></p>
	<p><label for="email">Email:</label><br /><input type="text" name="Email" id="email" size="30" /><br /></p>
<p><label for="Heard_Of">How did you hear of us:</label><br />
     <select name="Heard_Of" id="Heard_Of">
	 <option selected="selected">Search Engine</option>
	 <option>Friend</option>
	 <option>Referral from another site</option>
	 <option>Email</option>
	</select></p>
	<p><label for="comment">Message:</label><br /><textarea name="Comment" id="comment" rows="5" cols="30"></textarea><br /></p>
	<p><input type="submit" value="Submit" /> <input type="reset" value="Reset" name="reset" /></p>
</form>
