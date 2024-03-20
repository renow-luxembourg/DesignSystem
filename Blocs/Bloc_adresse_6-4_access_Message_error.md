```html
  <div class="form-group">
    <div class="form-group-label">
      <label for="postal-code">Code postal<span class="field-required">*</span></label>
    </div>
    <div class="form-group-field">
      <input type="text" id="postal-code" name="postal-code" class="form-field" autocomplete="postal-code" aria-invalid="true"  aria-describedby="postal-code-desc postal-code-error" required>
      <div class="alert alert--info"> 
        <p id="postal-code-desc">Saisir 1234 pour L-1234</p>
      </div>
       <div class="alert alert--error">  
        <p id="error-iban" class="error">Veuillez saisir un code postal valide (exemple : L-1234)</p>
      </div>
    </div>
  </div>
```