---
title: Contact
layout: page
---

# Contact

Voel je vrij om een berichtje te sturen.

<form action="https://formspree.io/joop@xs4all.nl" method="POST">
  <label for="naam">Naam</label>
  <input type="text" name="naam" id="naam" required />
  <label for="e-mail">E-mail</label>
  <input type="e-mail" name="_replyto" id="e-mail" required />
  <label for="bericht">Uw bericht</label>
  <textarea name="bericht" required></textarea>
  <input type="hidden" name="_next" value="{{site.baseurl}}/dank" />
  <input type="hidden" name="_language" value="nl" />
  <input type="text" name="_gotcha" style="display:none" />
  <input type="submit" value="Versturen" />
</form>

<small>Alle velden zijn verplicht.</small>
