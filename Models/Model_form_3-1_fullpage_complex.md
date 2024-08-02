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
        <div class="page-logo">
          <a href="//guichet.public.lu/fr/citoyens.html" title="Guichet.lu - Citoyens - Accueil">
            <img src="//guichet.public.lu/dam-assets/ctie/logo-guichet.svg" alt="Guichet.lu">
            <span class="logo-title">Guichet.lu - Citoyens</span>
          </a>
        </div>
        <div class="page-user">
          <div class="dropdown">
            <button id="page-user-dropdown" class="dropdown-toggle" type="button" aria-expanded="false" aria-controls="page-user-dropdown-menu">
              <span class="user-text">[User name/Anonymous]</span>
              <span class="user-icon"><svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 32.49 44" aria-hidden="true" focusable="false">
                <path class="icon" data-name="user" d="m16.53,0C21.23,0,25.04,3.81,25.04,8.51s-3.81,8.51-8.51,8.51-8.51-3.81-8.51-8.51S11.83,0,16.53,0h0m15.9,39.81v4.19H0v-4.19c-.13-4.34,1.12-8.62,3.57-12.2,5.65-7.08,15.97-8.23,23.05-2.58.66.53,1.27,1.1,1.84,1.72,2.89,3.72,4.3,8.37,3.97,13.07h-.01Z"></path>
                </svg>
              </span>
            </button>
            <div id="page-user-dropdown-menu" class="dropdown-menu">
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
    <main id="main" class="page-main" role="main">
      <div class="page-content">
        <div class="page-sidebar">
          <div class="cmp-progress-indicator">
            <h2 class="cpi-title">Etapes</h2>
            <nav class="cpi-navigation">
              <ul class="cpi-list">
                <li class="cpi-item cpi-item--completed">
                  <a href="#" class="cpi-item-text">Caractéristique de la demande <span class="cpi-status cpi-status--completed">
                      <svg class="icon icon--small" viewBox="0 0 24 24" width="24" height="24" aria-hidden="true" focusable="false">
                        <use xlink:href="#icon-cpi-completed" x="0" y="0"></use>
                      </svg>
                      <span class="at">Etape completée</span>
                    </span>
                  </a>
                  <button type="button" aria-controls="cpi-uid-1" aria-expanded="false">
                    <svg class="icon icon--small" viewBox="0 0 24 24" width="24" height="24" aria-hidden="true" focusable="false">
                      <use xlink:href="#icon-arrow-down" x="0" y="0"></use>
                    </svg>
                  </button>
                  <ul id="cpi-uid-1">
                    <li class="cpi-item">
                      <span class="cpi-item-text">Coordonnées de l'exploitant n°1</span>
                    </li>
                    <li class="cpi-item">
                      <span class="cpi-item-text">Coordonnées du requérant</span>
                    </li>
                    <li class="cpi-item">
                      <span class="cpi-item-text">Autorisations concernées par la démarche</span>
                    </li>
                  </ul>
                </li>
                <li class="cpi-item cpi-item--error cpi-item--current">
                  <a href="#" class="cpi-item-text">Volet général <span class="cpi-status cpi-status--error">
                      <svg class="icon icon--small" viewBox="0 0 24 24" width="24" height="24" aria-hidden="true" focusable="false">
                        <use xlink:href="#icon-cpi-error" x="0" y="0"></use>
                      </svg>
                      <span class="at">Etape problématique</span>
                    </span>
                  </a>
                  <button type="button" aria-controls="cpi-uid-2" aria-expanded="true">
                    <svg class="icon icon--small" viewBox="0 0 24 24" width="24" height="24" aria-hidden="true" focusable="false">
                      <use xlink:href="#icon-arrow-up" x="0" y="0"></use>
                    </svg>
                  </button>
                  <ul id="cpi-uid-2">
                    <li class="cpi-item">
                      <a href="#" class="cpi-item-text">Coordonnées de l'exploitant n°1</a>
                    </li>
                    <li class="cpi-item">
                      <a href="#" class="cpi-item-text">Coordonnées du requérant</a>
                    </li>
                    <li class="cpi-item">
                      <a href="#" class="cpi-item-text">Autorisations concernées par la démarche</a>
                    </li>
                    <li class="cpi-item cpi-item--error cpi-item--current">
                      <a href="#" class="cpi-item-text">Etablissements classés objets de la phase construction <span class="cpi-status cpi-status--error">
                          <svg class="icon icon--small" viewBox="0 0 24 24" width="24" height="24" aria-hidden="true" focusable="false">
                            <use xlink:href="#icon-cpi-error" x="0" y="0"></use>
                          </svg>
                          <span class="at">Etape problématique</span>
                        </span>
                      </a>
                      <button type="button" aria-controls="cpi-uid-3" aria-expanded="true">
                        <svg class="icon icon--small" viewBox="0 0 24 24" width="24" height="24" aria-hidden="true" focusable="false">
                          <use xlink:href="#icon-arrow-up" x="0" y="0"></use>
                        </svg>
                      </button>
                      <ul id="cpi-uid-3">
                        <li class="cpi-item cpi-item--error cpi-item--current">
                          <a href="#" class="cpi-item-text">Etablissements classés n°1 <span class="cpi-status cpi-status--error">
                              <svg class="icon icon--small" viewBox="0 0 24 24" width="24" height="24" aria-hidden="true" focusable="false">
                                <use xlink:href="#icon-cpi-error" x="0" y="0"></use>
                              </svg>
                              <span class="at">Etape problématique</span>
                            </span>
                          </a>
                          <button type="button" aria-controls="cpi-uid-4" aria-expanded="true">
                            <svg class="icon icon--small" viewBox="0 0 24 24" width="24" height="24" aria-hidden="true" focusable="false">
                              <use xlink:href="#icon-arrow-up" x="0" y="0"></use>
                            </svg>
                          </button>
                          <ul id="cpi-uid-4">
                            <li class="cpi-item cpi-item--error cpi-item--current">
                              <a href="#" class="cpi-item-text">Composant n°1 <span class="cpi-status cpi-status--error">
                                  <svg class="icon icon--small" viewBox="0 0 24 24" width="24" height="24" aria-hidden="true" focusable="false">
                                    <use xlink:href="#icon-cpi-error" x="0" y="0"></use>
                                  </svg>
                                  <span class="at">Etape problématique</span>
                                </span>
                              </a>
                              <button type="button" aria-controls="cpi-uid-5" aria-expanded="true">
                                <svg class="icon icon--small" viewBox="0 0 24 24" width="24" height="24" aria-hidden="true" focusable="false">
                                  <use xlink:href="#icon-arrow-up" x="0" y="0"></use>
                                </svg>
                              </button>
                              <ul id="cpi-uid-5">
                                <li class="cpi-item cpi-item--error">
                                  <a href="#" class="cpi-item-text">Elements connexes <span class="cpi-status cpi-status--error">
                                      <svg class="icon icon--small" viewBox="0 0 24 24" width="24" height="24" aria-hidden="true" focusable="false">
                                        <use xlink:href="#icon-cpi-error" x="0" y="0"></use>
                                      </svg>
                                      <span class="at">Etape problématique</span>
                                    </span>
                                  </a>
                                </li>
                                <li class="cpi-item cpi-item--current">
                                  <span class="cpi-item-text">Pièces jointes</span>
                                </li>
                              </ul>
                            </li>
                            <li class="cpi-item">
                              <a href="#" class="cpi-item-text">Composant-ajout</a>
                            </li>
                          </ul>
                        </li>
                        <li class="cpi-item cpi-item--completed">
                          <a href="#" class="cpi-item-text">Etablissement classé-ajout <span class="cpi-status cpi-status--completed">
                              <svg class="icon icon--small" viewBox="0 0 24 24" width="24" height="24" aria-hidden="true" focusable="false">
                                <use xlink:href="#icon-cpi-completed" x="0" y="0"></use>
                              </svg>
                              <span class="at">Etape completée</span>
                            </span>
                          </a>
                        </li>
                        <li class="cpi-item cpi-item--error">
                          <a href="#" class="cpi-item-text">Evaluation des incidences sur l'environnement (loi du 15 mars 2018) <span class="cpi-status cpi-status--error">
                              <svg class="icon icon--small" viewBox="0 0 24 24" width="24" height="24" aria-hidden="true" focusable="false">
                                <use xlink:href="#icon-cpi-error" x="0" y="0"></use>
                              </svg>
                              <span class="at">Etape problématique</span>
                            </span>
                          </a>
                        </li>
                      </ul>
                    </li>
                  </ul>
                </li>
                <li class="cpi-item">
                  <a href="#" class="cpi-item-text">Annexes</a>
                  <button type="button" aria-controls="cpi-uid-6" aria-expanded="false">
                    <svg class="icon icon--small" viewBox="0 0 24 24" width="24" height="24" aria-hidden="true" focusable="false">
                      <use xlink:href="#icon-arrow-down" x="0" y="0"></use>
                    </svg>
                  </button>
                  <ul id="cpi-uid-6">
                    <li class="cpi-item">
                      <span class="cpi-item-text">Coordonnées de l'exploitant n°1</span>
                    </li>
                    <li class="cpi-item">
                      <span class="cpi-item-text">Coordonnées du requérant</span>
                    </li>
                    <li class="cpi-item">
                      <span class="cpi-item-text">Autorisations concernées par la démarche</span>
                    </li>
                  </ul>
                </li>
                <li class="cpi-item cpi-item--error">
                  <a href="#" class="cpi-item-text">Liste des erreurs et avertissements <span class="cpi-status cpi-status--error">
                      <svg class="icon icon--small" viewBox="0 0 24 24" width="24" height="24" aria-hidden="true" focusable="false">
                        <use xlink:href="#icon-cpi-error" x="0" y="0"></use>
                      </svg>
                      <span class="at">Etape problématique</span>
                    </span>
                  </a>
                </li>
              </ul>
            </nav>
          </div>
        </div>
        <!-- Form -->
        <div class="page-text">
          <form>
            <div class="form-row field-info">
              <p class="mandatory-text"><span class="field-required">*</span>: champ obligatoire</p>
            </div>
            <fieldset>
              <legend>Signalétique</legend>
              <div class="form-group">
                <div class="form-group-label">
                  <label for="lastname">Nom<span class="field-required">*</span>
                  </label>
                </div>
                <div class="form-group-field">
                  <input id="lastname" name="lastname" type="text" class="form-field" autocomplete="family-name" required>
                </div>
              </div>
              <div class="form-group">
                <div class="form-group-label">
                  <label for="firstname">Prénom(s)</label>
                </div>
                <div class="form-group-field">
                  <input id="firstname" name="firstname" type="text" class="form-field" autocomplete="given-name">
                </div>
              </div>
            </fieldset>
            <fieldset>
              <legend>Coordonnées de contact</legend>
              <div class="form-group">
                <div class="form-group-label">
                  <label for="phone">Téléphone</label>
                </div>
                <div class="form-group-field">
                  <input id="phone" name="phone" type="tel" class="form-field" autocomplete="tel" aria-describedby="phone-desc">
                  <div class="alert alert--info" id="phone-desc">
                    <p>Indicatif du pays puis numéro (exemple : +352 12 345 678)</p>
                  </div>
                </div>
              </div>
              <div class="form-group">
                <div class="form-group-label">
                  <label for="email">E-mail (exemple : nom.prenom@domaine.lu)<span class="field-required">*</span>
                  </label>
                </div>
                <div class="form-group-field">
                  <input id="email" name="email" type="email" class="form-field" autocomplete="email">
                </div>
              </div>
            </fieldset>
            <div class="form-group">
              <div class="form-group-label">
                <label for="message">Message</label>
              </div>
              <div class="form-group-field">
                <textarea id="message" name="message"></textarea>
              </div>
            </div>
          </form>
        </div>
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
      </div>
    </main>
    <!-- Footer -->
    <footer class="page-footer" role="contentinfo">
      <h2 class="footer-title at">Pied de page</h2>
      <div class="page-footer-content">
        <div class="navigation-container">
          <ul class="nav nav--support">
            <li class="nav-item">
              <a href="./aide.html">Aide</a>
            </li>
            <li class="nav-item">
              <a href="./contact.html">Contact</a>
            </li>
            <li class="nav-item">
              <a href="./aspects-legaux.html">Aspects légaux</a>
            </li>
            <li class="nav-item">
              <a href="./accessibilite.html">Accessibilité</a>
            </li>
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