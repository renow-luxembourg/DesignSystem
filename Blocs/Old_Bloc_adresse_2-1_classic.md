```html
<fieldset>
  <legend>Address</legend>
  <fieldset class="cmp-form-options cmp-form-options--radio">
    <legend class="cmp-form-options__legend">Address Type</legend>
    <label class="cmp-form-options__field-label" for="physical-address">
      <input class="cmp-form-options__field cmp-form-options__field--radio" id="opt-physical-address" type="radio" name="address-type" value="physical-address">
      <span class="cmp-form-options__field-description">Physical address</span>
    </label>
    <label class="cmp-form-options__field-label" for="postal-box">
      <input class="cmp-form-options__field cmp-form-options__field--radio" id="opt-postal-box" type="radio" name="address-type" value="postal-box">
      <span class="cmp-form-options__field-description">P.O. box</span>
    </label>
    <label class="cmp-form-options__field-label" for="free-address">
      <input class="cmp-form-options__field cmp-form-options__field--radio" id="opt-free-address" type="radio" name="address-type" value="free-address">
      <span class="cmp-form-options__field-description">Free address</span>
    </label>
  </fieldset>
  <div class="form-group opt-physical-address-visible">
    <label for="number">Number</label>
    <input type="text" id="number" name="number" class="form-field">
  </div>
  <div class="form-group opt-physical-address-visible">
    <label for="street">Street</label>
    <input type="text" id="street" name="street" class="form-field" autocomplete="address-line1" required>
  </div>
  <div class="form-group opt-physical-address-visible">
    <label for="complement">Complement</label>
    <input type="text" id="complement" name="complement" class="form-field" autocomplete="address-line2">
  </div>

  <div class="form-group">
    <label for="postal-code">Postal code</label>
    <input type="text" id="postal-code" name="postal-code" class="form-field" autocomplete="postal-code" required>
  </div>
  <div class="form-group opt-free-address-visible">
    <label for="street-address">Postal address</label>
    <textarea id="street-address" name="street-address" autocomplete="street-address" required></textarea>
  </div>
  <div class="form-group">
    <label for="city">City</label>
    <input type="text" id="city" name="city" class="form-field" autocomplete="address-level2" required>
  </div>
  <div class="form-group opt-postal-box-visible">
    <label for="postal-code">P.O. box</label>
    <input type="text" id="postal-box" name="postal-box" class="form-field" required>
  </div>
  <div class="form-group">
    <label for="country">Country</label>
    <select id="country" name="country" class="form-field" autocomplete="country" required>
    </select>
  </div>
</fieldset>
```