# extension-ideas
Ideas for possible future TYPO3 extensions.

## adminpanel extended
- list the exact infos for each _INT object on the webpage (instead of just the count)
$GLOBALS['TSFE']->config['INTincScript']:

## grapejs integration
- backend module that enables users without html knowledge to click together email templates via **grapejs**
  - integration to **forms** extension
  - configurable html components (like the companys logo, footer, etc.)
  - template variables that correspond to input fields from a yaml form
  - allow for a (configurable) white-list of fluid viewhelpers in grapejs
  - create ready-to-use html components for grapejs as fluid templates in a custom extension 
  - translatable / multilanguage support
  - alternative plain text view for html emails
  - typo3 link builder integration in grapejs?
  - image upload
  - button to send test emails to a email adress
  - see https://github.com/artf/grapesjs-preset-newsletter

## automatically create backend user permissions
- configure default beusers und beuser group settings for newly setup TYPO3 sites with YAML
- make the YAML extendable - for instance, an extension provides its own suggestions for default permissions.
- executable in CLI mode

## forms validation
- easy to use frontend + server side ajax validation for **forms**

## search extension
- search solution for projects that are too small for solr / elasticsearch, without having to rely on a naive / weakly optimized mysql fulltext search
- maybe a readyonly sqlite database?   	 
- or some nosql database that runs on a typical php-only default server configuration?
- ideally as an extension to TYPO3 core's indexed_search. But **index_search** appears to be a hard-wired mess right now, that does not allow injecting an alternative search engine. So refactor the extension in the core?

## TYPO3 performance guide
- finish the performance guide

## slow queries
- Helper for automatically detecting slow (n+1) queries in Extbase ORM / Doctrine Query Builder

## chrome dev tools integration
- Clockwork (Chrome extension) integration for TYPO3 CMS.
- OR alternatively php-console integration with TYPO3: https://github.com/barbushin/php-console

## tattica integration
- advanced image loading queue / rules in the frontend with tattica.

## evaluate shepherd.js
- give backend editors a guided tutorial tour through the TYPO3 backend.
- customizable popups
- there appears to already be an ext called **guide**? -> check out

## live to stage/dev
- easy migration of db tables from a live instance to a stage/dev instance with reliable, automatic anonymization of data.

## extension blacklist
- automatically disallow the installation of a blacklist of extension keys.
