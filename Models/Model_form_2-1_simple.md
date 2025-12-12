```html
<form>
  <div class="form-row field-info">
    <p class="mandatory-text"><span class="field-required">*</span>: champ obligatoire</p>
  </div>
  <fieldset>
    <legend>Signalétique</legend>
    <div class="form-group">
      <div class="form-group-label">
        <label for="lastname">Nom<span class="field-required">*</span></label>
      </div>
      <div class="form-group-field">
        <input id="lastname" name="lastname" type="text" autocomplete="family-name" required>
      </div>
    </div>
    <div class="form-group">
      <div class="form-group-label">
        <label for="firstname">Prénom(s)</label>
      </div>
      <div class="form-group-field">
        <input id="firstname" name="firstname" type="text" autocomplete="given-name">
      </div>
    </div>
  </fieldset>
  <fieldset>
    <legend>Coordonnées de contact</legend>
    <div class="form-group">
      <div class="form-group-label">
        <label for="tel">Téléphone</label>
      </div>
      <div class="form-group-field">
        <input id="tel" name="tel" type="tel" autocomplete="tel" aria-describedby="info-tel">
        <div class="msg msg--info" id="info-tel"> 
          <p>Indicatif du pays puis numéro (exemple : +352 12 345 678)</p>
        </div>
      </div>
    </div>
    <div class="form-group">
      <div class="form-group-label">
        <label for="email">Adresse e-mail (format : nom.prenom@domaine.lu)<span class="field-required">*</span></label>
      </div>
      <div class="form-group-field">
        <input id="email" name="email" type="email" class="form-field" autocomplete="email">
      </div>
    </div>
  </fieldset>
  <div class="form-group">
    <div class="form-group-label">
      <label for="message">Message<span class="field-required">*</span></label>
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