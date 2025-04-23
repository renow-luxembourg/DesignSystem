```html
<fieldset>
  <legend>Personne physique</legend>
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
      <label for="firstname">Prénom(s)<span class="field-required">*</span></label>
	  <div class="tooltip">
      <button class="btn tooltip-button" type="button" aria-label="Aide sur le champ prénom(s)" aria-expanded="false">i</button>
      <div class="tooltip-content" data-popper-placement="bottom" style="margin: 5px 0 0 -5px">
        Si la personne n'a pas de prénom, veuillez saisir un tiret (-)
        <div class="tooltip-content-arrow"></div>
      </div>
    </div>
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
      <div class="alert alert--info" id="nin-desc"> 
        <p>Numéro à 13 chiffres (format: AAAAMMJJXXXXX)</p>
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
      <label for="birthdate">Date de naissance (JJ/MM/AAAA)<span class="field-required">*</span></label>
    </div>
    <div class="form-group-field">
      <input id="birthdate" name="birthdate" type="text" class="form-field" placeholder="jj/mm/aaaa" required>
    </div>
  </div>
  <div class="form-group">
    <div class="form-group-label">
      <label for="birthplace">Lieu de naissance<span class="field-required">*</span></label>
    </div>
    <div class="form-group-field">
      <input id="birthplace" name="birthplace" type="text" class="form-field" required>
    </div>
  </div>
</fieldset>
```