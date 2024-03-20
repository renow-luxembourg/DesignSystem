```html
<fieldset>
  <legend>Adresse</legend>
   <div class="form-group">
    <div class="form-group-label">
      <label for="street">Rue (et numéro de rue)<span class="field-required">*</span></label>
    </div>
    <div class="form-group-field">
      <input type="text" id="street" name="street" class="form-field" autocomplete="street-address" required>
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