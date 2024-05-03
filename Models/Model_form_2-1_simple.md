```html
<form>
  <div class="form-row field-info">
    <p class="mandatory-text"><span class="field-required">*</span>: obligatoires.</p>
  </div>
  <fieldset>
    <legend>Signalétique</legend>
    <div class="form-group">
      <div class="form-group-label">
        <label for="lastname">Nom<span class="field-required">*</span></label>
      </div>
      <div class="form-group-field">
        <input id="lastname" name="lastname" type="text" class="form-field" autocomplete="family-name" required>
      </div>
    </div>
    <div class="form-group">
      <div class="form-group-label">
        <label for="firstname">Prénom(s)</label>
      </div>
      <div class="form-group-field">
        <input id="firstname" name="firstname" type="text" class="form-field" autocomplete="given-name">
      </div>
    </div>
  </fieldset>
  <fieldset>
    <legend>Coordonnées de contact</legend>
    <div class="form-group">
      <div class="form-group-label">
        <label for="phone">Téléphone</label>
      </div>
      <div class="form-group-field">
        <input id="phone" name="phone" type="tel" class="form-field" autocomplete="tel" aria-describedby="phone-desc">
        <div class="alert alert--info" id="phone-desc"> 
          <p>Indicatif du pays puis numéro (exemple : +352 12 345 678)</p>
        </div>
      </div>
    </div>
    <div class="form-group">
      <div class="form-group-label">
        <label for="email">E-mail (exemple : nom.prenom@domaine.lu)<span class="field-required">*</span></label>
      </div>
      <div class="form-group-field">
        <input id="email" name="email" type="email" class="form-field" autocomplete="email">
      </div>
    </div>
  </fieldset>
  <div class="form-group">
    <div class="form-group-label">
      <label for="message">Message</label>
    </div>
    <div class="form-group-field">
      <textarea id="message" name="message"></textarea>
    </div>
  </div>
  <div class="form-row field--button">
    <button type="submit" class="btn btn-primary">Prévisualiser puis envoyer</button>
  </div>
</form>
```