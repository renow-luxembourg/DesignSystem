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
          <option value="BE">Belgium</option>
          <option value="DE">Germany</option>
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
      <label for="postal-box">Postal box <span class="field-required">*</span></label>
    </div>
    <div class="form-group-field">
      <input type="text" id="postal-box" name="postal-box" class="form-field" required>
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
      <label for="commune">Commune <span class="field-required">*</span></label>
    </div>
    <div class="form-group-field">
      <input type="text" id="commune" name="commune" class="form-field" autocomplete="address-level3" required>
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
</fieldset>
```