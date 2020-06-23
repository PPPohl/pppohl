---
layout: page
title: Test
permalink: /test/
---

https://docs.google.com/forms/d/e/1FAIpQLSdyiNRnL93or7idZUQO-IMfa__e5aqE-XeaAOhKREpDVARBOQ/viewform?usp=pp_url&entry.1618301866=TestVorname&entry.970278938=TestNachname

Hier wird getestet!

<form name="gform" id="gform" enctype="text/plain" action="https://docs.google.com/forms/d/e/1FAIpQLSdyiNRnL93or7idZUQO-IMfa__e5aqE-XeaAOhKREpDVARBOQ/formResponse?" target="hidden_iframe" onsubmit="submitted=true;">
  Vorname:<br>
  <input type="text" name="entry.1618301866" id="entry.1618301866"><br>
  Nachname:<br>
  <input type="text" name="entry.970278938" id="entry.970278938">
  <input type="submit" value="Submit">
</form>
<script src="assets/js/jquery.min.js"></script>
<script type="text/javascript">var submitted=false;</script>
<script type="text/javascript">
$('#gform').on('submit', function(e) {
  $('#gform *').fadeOut(2000);
  $('#gform').prepend('Your submission has been processed...');
  });
</script>
