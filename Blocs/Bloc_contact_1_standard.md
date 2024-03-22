```html
<fieldset>
  <legend>Coordonnées de contact</legend>
  <div class="form-group">
    <div class="form-group-label">
      <label for="phone">Téléphone</label>
    </div>
    <div class="form-group-field">
      <input id="phone" name="phone" type="text" autocomplete="tel" aria-describedby="phone-desc">
      <div class="alert alert--info"> 
      <p id="phone-desc">Indicatif du pays puis numéro (exemple : +352 12 345 678)</p>
    </div>
    </div>
  </div>
  <div class="form-group">
    <div class="form-group-label">
      <label for="email">E-mail (exemple : nom.prenom@domaine.lu)</label>
    </div>
    <div class="form-group-field">
      <input id="email" name="email" type="email" autocomplete="email">
    </div>
  </div>
  <div class="form-group">
    <div class="form-group-label">
      <label for="emailconfirm">Confirmer l'e-mail</label>
    </div>
    <div class="form-group-field">
      <input id="emailconfirm" name="emailconfirm" type="email">
    </div>
  </div>
</fieldset>
```