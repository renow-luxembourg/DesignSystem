```html
<!DOCTYPE html>
<html lang="fr">
  <head>[...]</head>
  <body>
    <!-- Skiplinks -->
    <div class="skiplinks">
      <a href="#main" data-href="#main">Aller au contenu</a>
    </div>
    <!-- Govbar -->
    <div id="govbar" class="govbar">
      <img src="https://cdn.public.lu/pictures/logos/gov/gov-light.png" alt="Gouvernement du Grand-Duché de Luxembourg" title="Gouvernement du Grand-Duché de Luxembourg">
    </div>
    <!-- Header -->
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
                <li>
                  <a src="./logout.html">Se déconnecter</a>
                </li>
              </ul>
            </div>
          </div>
        </div>
        <div class="page-title">
          <h1>[Titre de la démarche]</h1>
        </div>
      </div>
    </header>
    <!-- Sidebar -->
    <main id="main" class="page-main " role="main">
      <div class="page-sidebar">
        <div class="cmp-progress-indicator">
          <h2 class="cpi-title">Etapes</h2>
          <nav class="cpi-navigation">[Liste des étapes]</nav>
        </div>
      </div>
      <!-- Form -->
      <form>[Champs du Formulaire]</form>
      <!-- Action Bar -->
      <div class="action-toolbar-wrapper">
        <div class="action-toolbar">
          <div class="action-toolbar-content">
            <div class="action-toolbar-left">
              <button type="button" class="btn btn-link"> Reprendre plus tard </button>
              <button class="btn btn-bright">
                <span class="cmp-button__icon">
                  <svg class="icon icon--small" viewBox="0 0 24 24" width="24" height="24" aria-hidden="true" focusable="false">
                    <use xlink:href="#icon-arrow-left" x="0" y="0"></use>
                  </svg>
                </span>
                <span class="cmp-button__text">Précédent</span>
              </button>
              <button class="btn btn-bright">
                <span class="cmp-button__text">Suivant</span>
                <span class="cmp-button__icon">
                  <svg class="icon icon--small" viewBox="0 0 24 24" width="24" height="24" aria-hidden="true" focusable="false">
                    <use xlink:href="#icon-arrow-right" x="0" y="0"></use>
                  </svg>
                </span>
              </button>
            </div>
          </div>
        </div>
      </div>
    </main>
    <!-- Footer -->
    <footer class="page-footer" role="contentinfo">
      <h2 class="footer-title at">Pied de page</h2>
      <div class="page-footer-content">
        <div class="navigation-container">
          <ul class="nav nav--support">
            <li class="nav-item"><a href="./aide.html">Aide</a></li>
            <li class="nav-item"><a href="./contact.html">Contact</a></li>
            <li class="nav-item"><a href="./aspects-legaux.html">Aspects légaux</a></li>
            <li class="nav-item"><a href="./accessibilite.html">Accessibilité</a></li>
          </ul>
        </div>
      </div>
      <div class="page-copyright">
        <a class="renow" href="https://renow.public.lu" rel="noopener" target="_blank" title="Renow, votre guide en matière de qualité web gouvernemental luxembourgeois - Nouvelle fenêtre">
          <img alt="Renow, votre guide en matière de qualité web gouvernemental luxembourgeois" src="https://cdn.public.lu/pictures/logos/renow-hdpi.png">
        </a>
      </div>
    </footer>
    <a href="#top" class="back" title="Haut de page">
      <svg class="icon" viewBox="0 0 24 24" width="24" height="24" aria-hidden="true" focusable="false">
        <use xmlns:xlink="http://www.w3.org/1999/xlink" xlink:href="#icon-back-to-top" x="0" y="0">
        </use>
      </svg>
      <span>Haut de page</span>
    </a>
  </body>
</html> 
```