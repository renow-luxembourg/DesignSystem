```html
<fieldset>
  <legend>Signalétique</legend>
  <div class="form-group">
    <div class="form-group-label">
        <label for="name">Désignation / raison sociale<span class="field-required">*</span></label>
    </div>
    <div class="form-group-field">
        <input id="name" name="name" type="text" class="form-field" required>
    </div>
  </div>
  <div class="form-group">
    <div class="form-group-label">
        <label for="nin">Numéro d'identification luxembourgeois<span class="field-required">*</span></label>
    </div>
    <div class="form-group-field">
        <input id="nin" name="nin" type="text" class="form-field" aria-describedby="nin-desc" required>
        <div class="alert alert--info"> 
        <p id="nin-desc">Numéro à 11 chiffres (format: AAAAMMJJXXXXX)</p>
        </div>
    </div>
  </div>
  <div class="form-group">
    <div class="form-group-label">
        <label for="regcom">Numéro du registre de commerce luxembourgeois<span class="field-required">*</span></label>
    </div>
    <div class="form-group-field">
        <input id="regcom" name="regcom" type="text" class="form-field" aria-describedby="regcom-desc" pattern="^([A-Z][0-9]{1,6})$" required>
        <div class="alert alert--info"> 
        <p id="regcom-desc">Numéro à 7 caractères (format : une lettre puis 6 chiffres)</p>
        </div>
    </div>
  </div>
  <div class="form-group">
    <div class="form-group-label">
        <label for="tva">Numéro de TVA luxembourgeoise<span class="field-required">*</span></label>
    </div>
    <div class="form-group-field">
        <input id="tva" name="tva" type="text" class="form-field" aria-describedby="tva-desc" required>
        <div class="alert alert--info"> 
        <p id="tva-desc">Numéro à 10 caractères (format : LUXXXXXXXX)</p>
        </div>
    </div>
  </div>
  <div class="form-group">
    <div class="form-group-label">
        <label for="nace">Code NACE de l'activité principale<span class="field-required">*</span></label>
    </div>
    <div class="form-group-field">
        <select id="nace" name="nace" class="form-field" required>[…]</select>
    </div>
  </div>
  <div class="form-group">
    <div class="form-group-label">
        <label for="jur">Forme juridique<span class="field-required">*</span></label>
    </div>
    <div class="form-group-field">
        <select id="jur" name="jur" class="form-field" required>[…]</select>
    </div>
  </div>
  <div class="form-group">
    <div class="form-group-label">
        <label for="otherjur">Autre forme juridique<span class="field-required">*</span></label>
    </div>
    <div class="form-group-field">
        <input id="otherjur" name="otherjur" type="text" class="form-field" required>
    </div>
  </div>
</fieldset>
```