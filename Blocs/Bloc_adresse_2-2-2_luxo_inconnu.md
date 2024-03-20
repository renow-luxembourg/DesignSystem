```html
<fieldset>
  <legend>Adresse</legend>
  <fieldset class="cmp-form-options cmp-form-options--radio">
    [...]
  </fieldset>
  <div class="form-group">
    <div class="form-group-label">
      <label for="country">Pays<span class="field-required">*</span></label>
    </div>
    <div class="form-group-field">
      <select id="country" name="country" class="form-field" autocomplete="country" required>
        <option value="" selected disabled hidden>Veuillez choisir un pays</option>
        <option value="LU">Luxembourg</option>
        <optgroup label="Pays frontaliers">
          <option value="BE">Belgique</option>
          <option value="DE">Allemagne</option>
          <option value="FR">France</option>
        </optgroup>
        <optgroup label="Autres pays">
          <option value="AF">Afghanistan</option>
          <option value="AL">Albanie</option>
          [...]
        </optgroup>
      </select>
    </div>
  </div>
  <div class="form-group">
    <div class="form-group-label">
      <label for="postal-code">Code postal<span class="field-required">*</span></label>
    </div>
    <div class="form-group-field">
      <input type="text" id="postal-code" name="postal-code" class="form-field" autocomplete="postal-code" aria-describedby="postal-code-desc" required>
      <div class="alert alert--info"> 
        <p id="postal-code-desc">Saisir 1234 pour L-1234</p>
      </div>
    </div>
  </div>
  <div class="form-group">
    <div class="form-group-label">
      <label for="city">Localité<span class="field-required">*</span></label>
    </div>
    <div class="form-group-field">
      <input type="text" id="city" name="city" class="form-field" autocomplete="address-level2" required>
    </div>
  </div>
  <div class="form-group">
    <div class="form-group-label">
      <label for="commune">Commune<span class="field-required">*</span></label>
    </div>
    <div class="form-group-field">
      <input type="text" id="commune" name="commune" class="form-field" autocomplete="address-level3" required>
    </div>
  </div>
  <div class="form-group">
    <div class="form-group-label">
      <label for="street">Rue<span class="field-required">*</span></label>
    </div>
    <div class="form-group-field">
      <input type="text" id="street" name="street" class="form-field" required>
    </div>
  </div>
  <div class="form-group">
    <div class="form-group-label">
      <label for="street-number">Numéro de rue</label>
    </div>
    <div class="form-group-field">
      <input type="text" id="street-number" name="street-number" class="form-field">
    </div>
  </div>
  <div class="form-group">
    <div class="form-group-label">
      <label for="additional-address">Complément d'adresse</label>
    </div>
    <div class="form-group-field">
      <input type="text" id="additional-address" name="additional-address" class="form-field">
    </div>
  </div>
  <div class="form-options form-options--checkbox">
    <label class="form-options-label" for="checkbox">
      <input class="form-options-field form-options-field--checkbox" name="checkbox" id="checkbox" type="checkbox" checked>
      <span class="form-options-description">Je n'ai pas trouvé l'adresse dans la listet</span>
    </label>
  </div>
</fieldset>
```