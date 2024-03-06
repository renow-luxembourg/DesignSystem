```html
<header class="page-header">
  <div class="page-header-content">
    <div class="page-logo">[lien-image du logo]</div>
    <div class="page-user">
      <div class="dropdown">
        <button id="page-user-dropdown" class="dropdown-toggle" type="button" aria-expanded="false" aria-controls="page-user-dropdown-menu">
          <span class="user-text">[User name/Anonymous]</span>
        </button>
        <div id="page-user-dropdown-menu">
          <ul>
            <li>[...]</li>
            <li><a src="./logout.html">Se déconnecter</a></li>
          </ul>
        </div>
      </div>
    </div>
    <div class="page-langs">
      <nav role="navigation" class="languagenavigation" aria-label="Choix de la langue">
        <ul class="languagenavigation__group">
          <li class="languagenavigation__item">
            <a class="languagenavigation__item-link" hreflang="fr" lang="fr" rel="alternate" title="fr - Français" href="/fr.html" aria-current="true" >
              <span>fr</span><span>Français</span>
            </a>
          </li>
          <li class="languagenavigation__item">
            <a class="languagenavigation__item-link" hreflang="de" lang="de" rel="alternate" title="de - Deutsch" href="/de.html">
              <span>de</span><span>Deutsch</span>
            </a>
          </li>
          <li class="languagenavigation__item">
            <a class="languagenavigation__item-link" hreflang="en" lang="en" rel="alternate" title="en - English" href="/en.html">
              <span>en</span><span>English</span>
            </a>
          </li>
        </ul>
      </nav>
    </div>
    <div class="page-title">
      <h1>[Titre de la démarche]</h1>
    </div>
  </div>
</header>
```