# shopify-ga4


For integrating shopify with ga4, with purchase and ecom events


Step 1.

Create gtm account/ get access to existing if found with tag assistant

Step 2. 

Ensure gtm is installed with the header code added to the theme.liquid and additional checkout scripts in settings

Step 3.

copy code inside additional-checkout-code file to end of additional checkout scripts

Step 4.

copy code inside theme-snippet-datalayer file into new theme snippet

product-datalayer.liquid

Step 5. 

add snippet to theme.liquid with code before </body>

{% render 'product-datalayer' %}

Step 6. 

import tag-template into tag manager -> admin -> important template

use current workspace and merge tags 

Step 7.

Go to variables and update the measurement id variable

Step 7.

create test item for $0 in shopify backend, no stock monitoring, disable storefronts besides online store

Step 8.

click preview and monitor preview window while browsing website 

view item should appear on product view, purchase on product purchase

Step 9. 

remove the test item

submit the tag manager to be a new version, name appropriately

