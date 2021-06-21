---
layout: page
#
# Content
#
title: "Inscription"
teaser: ""
header:
    image_fullwidth: "berges.jpg"
    permalink: "/"
---

Suite au passage de la conférence en mode virtuel, l'inscription à l'édition 2021 de Compas est désormais gratuite. Merci tout de même de remplir le formulaire suivant avant le **30 juin 2021**:


<form id="fs-frm" name="registration-form" accept-charset="utf-8" action="https://formspree.io/f/mleankrk" method="post">
  <fieldset id="fs-frm-inputs">
    <label for="full-name">Identité</label>
    <input type="text" name="name" id="full-name" placeholder="Prénom Nom" required="">
    <label for="email-address">Adresse mail</label>
    <input type="email" name="_replyto" id="email-address" required="">
    <label for="affil">Affiliation</label>
    <input type="text" name="affil_" id="affil" placeholder="Nom du laboratoire/entreprise" required="">
    <label for="ville">Ville</label>
    <input type="text" name="ville_" id="ville" placeholder="Ville" required="">
    <label for="pays">Pays</label>
    <input type="text" name="pays_" id="pays" placeholder="France" required="">
    <label for="theme">Thème principal</label>
     <select name="theme_" required="">
        <option value="Select" selected="" disabled="">Thèmes</option>
      	<option value="A">Architecture</option>
      	<option value="P">Parallélisme</option>
      	<option value="S">Système</option>
      	<option value="TR">Temps-réel</option>
      </select>
    <input type="hidden" name="_subject" id="email-subject" value="Registration Form Submission">
  </fieldset>
    <input type="submit" value="S'inscrire">

</form>