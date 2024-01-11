```html
<div class="form-group field-error">
  <div class="form-group-label">
    <label for="date">Label <span class="field-required">*</span></label>
    <div class="tooltip">
      <button type="button" aria-label="Help on date label field" class="tooltip-btn">i</button>
      <div class="tooltip-content" role="status">
        <p>Example and non-essential help about date label field</p>
      </div>
    </div>
  </div>
  <div class="form-group-field">
    <input id="date" name="datefield" type="date" aria-describedby="desc-date error-date" aria-invalid="true">
    <div class="alert alert--info">
      <p id="desc-date">Help message</p>
    </div>
    <div class="alert alert--error">
      <p id="error-date" class="error">Error message</p>
    </div>
  </div>
</div>
```