```html
<fieldset>
  <legend>Adresse</legend>
  <fieldset class="cmp-form-options cmp-form-options--radio">
    [...]
  </fieldset>
  <div class="form-group">
    <div class="form-group-label">
      <label for="line1">Ligne 1</label>
    </div>
    <div class="form-group-field">
      <input type="text" id="line1" name="line1" class="form-field" autocomplete="address-line1">
    </div>
  </div>
  <div class="form-group">
    <div class="form-group-label">
      <label for="line2">Ligne 2</label>
    </div>
    <div class="form-group-field">
      <input type="text" id="line2" name="line2" class="form-field" autocomplete="address-line2">
    </div>
  </div>
  <div class="form-group">
    <div class="form-group-label">
      <label for="line3">Ligne 3</label>
    </div>
    <div class="form-group-field">
      <input type="text" id="line3" name="line3" class="form-field" autocomplete="address-line3">
    </div>
  </div>
  <div class="form-group">
    <div class="form-group-label">
      <label for="postal-code">Code postal<span class="field-required">*</span></label>
    </div>
    <div class="form-group-field">
      <input type="text" id="postal-code" name="postal-code" class="form-field" autocomplete="postal-code" required>
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
</fieldset>
```