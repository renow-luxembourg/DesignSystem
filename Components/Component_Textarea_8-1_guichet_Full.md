```html
<div class="form-group field-error">
  <div class="form-group-label">
    <label for="textarea">Label <span class="field-required">*</span></label>
    <div class="tooltip">
      <button type="button" aria-label="Help on textarea label" class="tooltip-btn">i</button>
      <div class="tooltip-content" role="status">
        <p>Example and non-essential help about textarea</p>
      </div>
    </div>
  </div>
  <div class="form-group-field from-field-wrapper--counter">
    <p id="counter-textarea" class="form-counter" role="status">
      <span class="counter-value">0</span>/
      <span class="counter-total">13</span>
    </p>
    <textarea id="textarea" name="textarea" placeholder="Placeholder text" aria-describedby="desc-textarea counter-textarea error-textarea" aria-invalid="true" required></textarea>
    <div class="alert alert--info">
      <p id="desc-textarea">Help message</p>
    </div>
    <div class="alert alert--error">
      <p id="error-textarea" class="error">Error message</p>
    </div>
  </div>
</div>
```
