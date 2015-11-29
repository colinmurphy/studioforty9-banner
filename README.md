# StudioForty9 Banner Module

A simple Magento module which will add a banner to your site's header.

## 1. Installation

### 1.1. Composer

In your composer file you would add the following:

     {
         "repositories": [
             {
                 "type": "composer",
                 "url": "http://packages.firegento.com"
             },
             {
                 "url": "https://github.com/colinmurphy/studioforty9-banner.git",
                 "type": "git"
             }
         ],
         "require": {
             "magento-hackathon/magento-composer-installer": "*",
             "colinmurphy/studioforty9-banner": "dev-master"
         },
         "extra": {
            "magento-deploystrategy": "copy",
            "magento-force": true,
            "magento-root-dir": "./"
         }
     }


### 1.2. Modman
    
    modman init
    modman clone git@github.com:colinmurphy/studioforty9-banner.git