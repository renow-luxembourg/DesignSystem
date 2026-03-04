```html
<fieldset>
  <legend>Adresse</legend>
   <div class="form-group">
    <div class="form-group-label">
      <label for="street">Rue (et numéro de rue)<span class="field-required">*</span></label>
    </div>
    <div class="form-group-field">
      <input type="text" id="street" name="street" class="form-field" autocomplete="address-line1" required>
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
  [...]
</fieldset>
```