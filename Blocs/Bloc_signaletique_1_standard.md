```html
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
  <div class="form-group">
    <div class="form-group-label">
      <label for="nin">Numéro d'identification national<span class="field-required">*</span></label>
    </div>
    <div class="form-group-field">
      <input id="nin" name="nin" type="text" class="form-field" aria-describedby="nin-desc">
      <div class="alert alert--info"> 
        <p id="nin-desc">Numéro à 13 chiffres (format: AAAAMMJJXXXXX)</p>
      </div>
    </div>
  </div>
  <div class="form-options form-options--checkbox">
    <label class="form-options-label" for="nin-unknown">
      <input class="form-options-field form-options-field--checkbox" name="nin-unknown" id="nin-unknown" type="checkbox">
      <span class="form-options-description">Numéro d'identification national inconnu</span>
    </label>
  </div>
  <div class="form-group">
    <div class="form-group-label">
      <label for="birthdate">Date de naissance<span class="field-required">*</span></label>
    </div>
    <div class="form-group-field">
      <input id="birthdate" name="birthdate" type="date" class="form-field" required>
    </div>
  </div>
</fieldset>
```