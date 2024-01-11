```html
<fieldset>
  <legend>Address</legend>
  <div class="form-group">
    <label for="street-address">Postal address</label>
    <textarea id="street-address" name="street-address" autocomplete="street-address"></textarea>
  </div>
  <div class="form-group">
    <label for="city">City</label>
    <input type="text" id="city" name="city" class="form-field" autocomplete="address-level2">
  </div>
  <div class="form-group">
    <label for="postal-code">Postal code</label>
    <input type="text" id="postal-code" name="postal-code" class="form-field" autocomplete="postal-code">
  </div>
  <div class="form-group">
    <label for="country">Country</label>
    <select id="country" name="country" class="form-field" autocomplete="country">
      <option value="" selected disabled hidden>Select a country</option>
      <option value="LB">Luxembourg</option>
      <option value="FR">France</option>
      <option value="BE">Belgium</option>
      <option value="DE">Germany</option>
      <option value="NL">Netherlands</option>
      <option value="CH">Switzerland</option>
    </select>
  </div>
</fieldset>
```