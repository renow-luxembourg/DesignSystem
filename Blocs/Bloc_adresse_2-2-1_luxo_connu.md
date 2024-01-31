```html
<fieldset>
  <legend>Address</legend>
  <fieldset class="cmp-form-options cmp-form-options--radio">
    [...]
  </fieldset>
  <div class="form-group">
    <label for="country">Country <span class="field-required">*</span></label>
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
  <div class="form-group">
    <label for="postal-code">Postal code <span class="field-required">*</span></label>
    <input type="text" id="postal-code" name="postal-code" class="form-field" autocomplete="postal-code" required>
  </div>
  <div class="form-group">
    <label for="city">City <span class="field-required">*</span></label>
    <select id="city" name="city" class="form-field" required>
      <option value="" selected disabled hidden>Select a city based on the postal code entered</option>
    </select>
  </div>
  <div class="form-group">
    <label for="street">Street <span class="field-required">*</span></label>
	<select id="street" name="street" class="form-field" required>
      <option value="" selected disabled hidden>Select a street based on the previous fields entered</option>
    </select>
  </div>
    <div class="form-group">
    <label for="street-number">Street number</label>
    <select id="street-number" name="street-number" class="form-field">
      <option value="" selected disabled hidden>Select a street number based on the previous fields entered</option>
    </select>
  </div>
  <div class="form-group">
    <label for="additional-address">Additional address</label>
    <input type="text" id="additional-address" name="additional-address" class="form-field">
  </div>
  <div class="form-options form-options--checkbox">
    <label class="form-options-label" for="checkbox">
      <input class="form-options-field form-options-field--checkbox" name="checkbox" id="checkbox" type="checkbox">
      <span class="form-options-description">I couldn't find the address in the list</span>
    </label>
  </div>
</fieldset>
```