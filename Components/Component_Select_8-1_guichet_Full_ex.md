```html
<div class="form-group field-error">
  <div class="form-group-label">
    <label for="select">Label<span class="field-required">*</span></label>
    <div class="tooltip">
      <button type="button" aria-label="Help on select label" class="tooltip-btn">i</button>
      <div class="tooltip-content" role="status">
        <p>Example and non-essential help about select</p>
      </div>
    </div>
  </div>
  <div class="form-group-field">
    <select id="select" name="select" class="form-field" aria-describedby="desc-select error-select" aria-invalid="true" required>
      <option value="" selected disabled hidden>Preferred language</option>
      <option value="EN">English</option>
      <option value="FR">French</option>
      <option value="DE">German</option>
      <option value="LB">Luxembourgish</option>
      <option value="PT">Portuguese</option>
    </select>
    <div class="alert alert--info" id="desc-select">
      <p>Help message</p>
    </div>
    <div class="alert alert--error" id="error-select">
      <p class="error">Error message</p>
    </div>
  </div>
</div>
```
