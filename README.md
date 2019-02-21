# extension-ideas
Ideas for possible future TYPO3 extensions.

## grapejs integration
- backend module that enables users without html knowledge to click together email templates via **grapejs**
  - integration to **forms** extension
  - configurable html components (like the companys logo, footer, etc.)

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
