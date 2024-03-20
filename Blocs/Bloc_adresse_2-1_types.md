```html
<fieldset class="form-options form-options--radio">
  <legend class="form-options-legend">Type d'adresse<span class="field-required">*</span></legend>
  <ul class="form-options-content">
    <li class="form-options-group">
      <label class="form-options-label" for="physical-address">
        <input class="form-options-field form-options-field--radio" id="opt-physical-address" type="radio" name="address-type" value="PH">
        <span class="form-options-field-description">Adresse physique</span>
      </label>
    </li>
    <li class="form-options-group">
      <label class="form-options-label" for="postal-box">
        <input class="form-options-field form-options-field--radio" id="opt-postal-box" type="radio" name="address-type" value="BP">
        <span class="form-options-field-description">Boîte postale</span>
      </label>
    </li>
    <li class="form-options-group">
      <label class="form-options-label" for="biguser-box">
        <input class="form-options-field form-options-field--radio" id="opt-biguser-box" type="radio" name="address-type" value="BU">
        <span class="form-options-field-description">Code postal dédié</span>
      </label>
    </li>
    <li class="form-options-group">
      <label class="form-options-label" for="free-address">
        <input class="form-options-field form-options-field--radio" id="opt-free-address" type="radio" name="address-type" value="FF">
        <span class="form-options-field-description">Adresse libre</span>
      </label>
    </li>
  </ul>
</fieldset>
```