```html
<fieldset>
  <legend>Coordonnées bancaires</legend>
  <div class="form-group">
    <div class="form-group-label">
      <label for="name">Titulaire du compte</label>
    </div>
    <div class="form-group-field">
      <input id="name" name="name" type="text" class="form-field" autocomplete="name">
    </div>
  </div>
  <div class="form-group">
    <div class="form-group-label">
      <label for="bank">Nom de la banque</label>
    </div>
    <div class="form-group-field">
      <input id="bank" name="bank" type="text" class="form-field">
    </div>
  </div>
  <div class="form-group">
    <div class="form-group-label">
      <label for="iban">Numéro de compte (IBAN)</label>
    </div>
    <div class="form-group-field">
      <input id="iban" name="iban" type="text" class="form-field" aria-describedby="iban-desc">
      <div class="alert alert--info" id="iban-desc"> 
        <p>Numéro entre 14 et 34 position (Numéro de compte renseigné sur le relevé d'identité bancaire tel que : LU00 0000 0000 0000 0000)</p>
      </div>
    </div>
  </div>
  <div class="form-group">
    <div class="form-group-label">
      <label for="bic">Code BIC</label>
    </div>
    <div class="form-group-field">
      <input id="bic" name="bic" type="text" class="form-field" aria-describedby="bic-desc">
      <div class="alert alert--info" id="bic-desc"> 
        <p>Numéro à 8 ou 11 positions (code BIC renseigné sur le relevé d'identité bancaire)
        </p>
      </div>
    </div>
  </div>
</fieldset>
```