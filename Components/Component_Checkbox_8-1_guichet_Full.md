```html
<div class="form-options form-options--checkbox field-error">
  <label class="form-options-label" for="checkbox">
    <input class="form-options-field form-options-field--checkbox" name="checkbox" id="checkbox" type="checkbox" aria-describedby="error-checkbox info-checkbox" aria-invalid="true" >
    <span class="form-options-description">Label<span class="field-required">*</span></span>
    <div class="tooltip">
      <button type="button" aria-label="Help message about this field" class="tooltip-btn">i</button>
      <div class="tooltip-content" role="status">
        <p>Non-essential help message</p>
      </div>
    </div>
  </label>
  <div class="alert alert--info" id="info-checkbox"> 
      <p>Help message</p>
  </div>
  <div class="alert alert--error" id="error-checkbox">  
    <p class="error">Error message</p>
  </div>
</div>
```

