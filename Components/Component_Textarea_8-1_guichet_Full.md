```html
<div class="form-group field-error">
  <div class="form-group-label">
    <label for="textarea">Label<span class="field-required">*</span></label>
    <div class="tooltip">
      <button type="button" aria-label="Aide sur le champ Label" class="tooltip-btn">i</button>
      <div class="tooltip-content" role="status">
        <p>Exemple de texte</p>
      </div>
    </div>
  </div>
  <div class="form-group-field from-field-wrapper--counter">
    <p id="counter-textarea" class="form-counter" role="status">
      <span class="counter-value">0</span>/
      <span class="counter-total">200</span>
    </p>
    <textarea id="textarea" name="textarea" placeholder="Placeholder" aria-describedby="desc-textarea counter-textarea error-textarea" aria-invalid="true" required></textarea>
    <div class="alert alert--info" id="desc-textarea">
      <p>Message d'aide</p>
    </div>
    <div class="alert alert--error" id="error-textarea">
      <p class="error">Message d'erreur</p>
    </div>
  </div>
</div>
```
