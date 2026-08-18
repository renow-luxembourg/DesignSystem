```html
<fieldset>
  <legend>Coordonnées de contact</legend>
  <div class="form-group">
    <div class="form-group-label">
      <label for="phone">Téléphone</label>
    </div>
    <div class="form-group-field">
      <input id="phone" name="phone" type="tel" class="form-field" autocomplete="tel" aria-describedby="phone-desc">
      <div class="alert alert--info" id="phone-desc"> 
        <p>Indicatif du pays puis numéro (format : +352 xx xxx xxx)</p>
      </div>
    </div>
  </div>
  <div class="form-group">
    <div class="form-group-label">
      <label for="email">Adresse e-mail (format : contact@example.com) </label>
    </div>
    <div class="form-group-field">
      <input id="email" name="email" type="email" class="form-field" autocomplete="email">
    </div>
  </div>
</fieldset>
```