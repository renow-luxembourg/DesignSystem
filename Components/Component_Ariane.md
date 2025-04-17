```html
<nav role="navigation" class="cmp-breadcrumb" aria-label="vous êtes ici">
    <ol class="cmp-breadcrumb__list" itemscope itemtype="http://schema.org/BreadcrumbList">
            <li class="cmp-breadcrumb__item" itemscope itemprop="itemListElement" itemtype="http://schema.org/ListItem">
                <a class="cmp-breadcrumb__link" href="#/" itemprop="item">
					<span itemprop="name">Accueil</span>
					<meta itemprop="position" content="0">
				</a>
            </li>
            <li class="cmp-breadcrumb__item" itemscope itemprop="itemListElement" itemtype="http://schema.org/ListItem">
                <a class="cmp-breadcrumb__link" href="#/page-1.html" itemprop="item">
					<span itemprop="name">Page 1</span>
					<meta itemprop="position" content="1">
				</a>
            </li>
			<li class="cmp-breadcrumb__item" itemscope itemprop="itemListElement" itemtype="http://schema.org/ListItem">
                <a class="cmp-breadcrumb__link" href="#/page-1/page-2.html" itemprop="item">
					<span itemprop="name">Page 2</span>
					<meta itemprop="position" content="2">
				</a>
            </li>
            <li class="cmp-breadcrumb__item cmp-breadcrumb__item--active" itemscope itemprop="itemListElement" itemtype="http://schema.org/ListItem">
				<a class="cmp-breadcrumb__link" itemprop="item" aria-current="page">
					<span itemprop="name">Page courante</a>
					<meta itemprop="position" content="3">
				</a>
            </li>
        </ol>
    </div>
</nav>
```