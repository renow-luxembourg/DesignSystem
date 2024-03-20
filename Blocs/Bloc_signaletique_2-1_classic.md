```html
<fieldset>
  <legend>Identification form</legend>
  <div class="form-group">
    <label for="firstname">Firstname<span class="field-required">*</span></label>
    <input type="text" id="firstname" name="firstname" class="form-field" autocomplete="given-name" required>
  </div>
  <div class="form-group">
    <label for="lastname">Lastname<span class="field-required">*</span></label>
    <input type="text" id="lastname" name="lastname" class="form-field" autocomplete="family-name" required>
  </div>
  <div class="form-group">
    <label for="birthplace">Localité de naissance<span class="field-required">*</span></label>
    <input type="text" id="birthplace" name="birthplace" class="form-field" required>
  </div>
  <div class="form-group">
    <label for="deathplace">Localité de décès</label>
    <input type="text" id="deathplace" name="deathplace" class="form-field">
  </div>
  <div class="form-group">
    <label for="ssn">Social security number<span class="field-required">*</span></label>
    <p id="ssn-counter" role="status">
      <span class="counter-value">0</span>/
      <span class="counter-total">13</span>
    </p>
    <input type="text" id="ssn" name="ssn" class="form-field" aria-describedby="ssn-counter ssn-help" required>
    <p id="ssn-help">Enter a 13 digits number</p>
  </div>
  <div class="form-group">
    <label for="doc">Numéro de dossier</label>
    <input type="text" id="doc" name="doc" class="form-field" aria-describedby="doc-help">
    <p id="doc-help">Help message ???</p>
  </div>
  <div class="form-group">
    <label for="email">Email<span class="field-required">*</span></label>
    <div class="cmp-tooltip">
      <button type="button" aria-label="Help on Email field" class="cmp-tooltip-btn">i</button>
      <div class="cmp-tooltip-content" role="status">
       <p hidden>Example : firstname.lastname@doamin.lu</p>
      </div>
    </div>
    <input type="email" id="email" name="email" class="form-field" autocomplete="email" required>
  </div>
  <div class="form-group">
    <label for="phone">Phone<span class="field-required">*</span></label>
    <div class="cmp-tooltip">
      <button type="button" aria-label="Help on Phone field" class="cmp-tooltip-btn">i</button>
      <div class="cmp-tooltip-content" role="status">
        <p hidden>Please select your country extension</p>
      </div>
    </div>
    <input type="tel" id="phone" name="phone" class="form-field" autocomplete="tel" required>
  </div>
</fieldset>
```