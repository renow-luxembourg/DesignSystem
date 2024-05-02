```html
<div class="form-group field-error">
  <div class="form-group-label">
    <label for="textfield">Label<span class="field-required">*</span></label>
    <div class="tooltip">
      <button type="button" aria-label="Help on textfield label" class="tooltip-btn">i</button>
      <div class="tooltip-content" role="status">
        <p>Example and non-essential help about this textfield</p>
      </div>
    </div>
  </div>
  <div class="form-group-field from-field-wrapper--suffix from-field-wrapper--counter">
    <p id="counter-textfield" class="form-counter" role="status">
      <span class="counter-value">0</span>/
      <span class="counter-total">13</span>
    </p>
    <input type="text" id="textfield" name="textfield" class="form-field" aria-invalid="true" aria-describedby="desc-textfield suffix-textfield counter-textfield error-textfield" placeholder="Placeholder text" required>
    <p id="suffix-textfield" class="form-field-suffix">
      <span aria-hidden="true">€</span>
      <span class="sr-only">amount in euros</span>
    </p>
    <div class="alert alert--info" id="desc-textfield">  
      <p>Help message</p>
    </div>
    <div class="alert alert--error" id="error-textfield">  
      <p class="error">Error message</p>
    </div>
  </div>
</div>
```
