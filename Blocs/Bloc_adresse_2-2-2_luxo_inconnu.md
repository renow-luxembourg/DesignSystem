```html
<fieldset>
  <legend>Address</legend>
  <fieldset class="cmp-form-options cmp-form-options--radio">
    [...]
  </fieldset>
  <div class="form-group">
    <div class="form-group-label">
      <label for="country">Country <span class="field-required">*</span></label>
    </div>
    <div class="form-group-field">
      <select id="country" name="country" class="form-field" autocomplete="country" required>
        <option value="" selected disabled hidden>Select a country</option>
        <option value="LB">Luxembourg</option>
        <optgroup label="Pays frontaliers">
          <option value="FR">France</option>
          <option value="BE">Belgium</option>
          <option value="DE">Germany</option>
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
      <label for="postal-code">Postal code <span class="field-required">*</span></label>
    </div>
    <div class="form-group-field">
      <input type="text" id="postal-code" name="postal-code" class="form-field" autocomplete="postal-code" required>
    </div>
  </div>
  <div class="form-group">
    <div class="form-group-label">
      <label for="city">City <span class="field-required">*</span></label>
    </div>
    <div class="form-group-field">
      <input type="text" id="city" name="city" class="form-field" autocomplete="address-level2" required>
    </div>
  </div>
  <div class="form-group">
    <div class="form-group-label">
      <label for="street">Street <span class="field-required">*</span></label>
    </div>
    <div class="form-group-field">
      <input type="text" id="street" name="street" class="form-field" required>
    </div>
  </div>
  <div class="form-group">
    <div class="form-group-label">
      <label for="street-number">Street number</label>
    </div>
    <div class="form-group-field">
      <input type="text" id="street-number" name="street-number" class="form-field">
    </div>
  </div>
  <div class="form-group">
    <div class="form-group-label">
      <label for="additional-address">Additional address</label>
    </div>
    <div class="form-group-field">
      <input type="text" id="additional-address" name="additional-address" class="form-field">
    </div>
  </div>
  <div class="form-options form-options--checkbox">
    <label class="form-options-label" for="checkbox">
      <input class="form-options-field form-options-field--checkbox" name="checkbox" id="checkbox" type="checkbox" checked>
      <span class="form-options-description">I couldn't find the address in the list</span>
    </label>
  </div>
</fieldset>
```