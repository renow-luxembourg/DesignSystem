```html
<div class="form-group">
  <div class="form-group-label">
    <label for="recipient">Recipient</label>
  </div>
  <div class="form-group-field">
    <div class="infobox">
      <button type="button" class="infobox-btn" aria-label="Help on Recipient field"  title="Help on Recipient field" aria-haspopup="dialog">?</button>
    </div>
    <input type="text" id="recipient" name="recipient" class="form-field" aria-describedby="infobox-recipient-content">
  </div>
</div>

<div id="infobox-recipient" role="dialog" aria-modal="true" aria-labelledby="infobox-recipient-title">
  <h2 id="infobox-recipient-title">Help on Recipient field</h2>
  <button type="button" id="infobox-recipient-close">Close</button>
  <div id="infobox-recipient-content">
    <h3>Legal reference Art. 5.3</h3>
    <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit...</p>
  </div>
</div>
```
