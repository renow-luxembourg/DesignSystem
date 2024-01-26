```html
<fieldset class="form-options form-options--radio" aria-describedby="desc-radio error-radio">
  <legend class="form-options-legend">Country of residence <span class="field-required">*</span>
    <div class="tooltip">
      <button type="button" aria-label="Help message about this field" class="tooltip-btn">i</button>
      <div class="tooltip-content" role="status">
        <p>Non-essential help message</p>
      </div>
    </div>
  </legend>
  <div class="alert alert--info">  
    <p id="desc-radio">Help message</p>
  </div>
  <ul class="form-options-content">
    <li class="form-options-group">
      <label class="form-options-label" for="LB">
        <input class="form-options-field form-options-field--radio" id="LB" type="radio" name="radio-group" value="LB">
        <span class="form-options-description">Luxembourg</span>
      </label>
    </li>
    <li class="form-options-group">
      <label class="form-options-label" for="FR">
        <input class="form-options-field form-options-field--radio" id="FR" type="radio" name="radio-group" value="FR">
        <span class="form-options-description">France</span>
      </label>
    </li>
    <li class="form-options-group">
      <label class="form-options-label" for="BE">
        <input class="form-options-field form-options-field--radio" id="BE" type="radio" name="radio-group" value="BE">
        <span class="form-options-description">Belgium</span>
      </label>
    </li>
    <li class="form-options-group">
      <label class="form-options-label" for="DE">
        <input class="form-options-field form-options-field--radio" id="DE" type="radio" name="radio-group" value="DE">
        <span class="form-options-description">Germany</span>
      </label>
    </li>
    <li class="form-options-group">
      <label class="form-options-label" for="other">
        <input class="form-options-field form-options-field--radio" id="other" type="radio" name="radio-group" value="other">
        <span class="form-options-description">Other</span>
      </label>
    </li>
  </ul>
  <div class="alert alert--error">
    <p id="error-radio" class="error">Error message</p>
  </div>
</fieldset>
```
