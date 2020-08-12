Coaltion Technologies Theme Test
============
Task Description: Create a collection template which will show all the color variations of the product as an individual product on the collection page. Here is the link to the standard template and here is the collection page which shows color variations as products. The new collection template name should be collection.with-variants.liquid

If you do not have a Shopify sandbox account, you can create a trial Shopify store account for this skill test.

Here is the sample CSV file to use: https://cdn.shopify.com/s/files/1/0261/3090/7210/files/products_export.csv

Base theme to use: Debut https://themes.shopify.com/themes/debut/styles/default

Standard Collection Page: https://ctrecruiting.myshopify.com/collections/standard

Collection with Color Variation: https://ctrecruiting.myshopify.com/collections/show-color-variations

NOTE: You may have to right click links to be sure you are not sent to a different page.

How to submit test:

Please make sure you’ve followed the above instructions before submitting your skills test. Please export your theme and upload your zip file in the job application page.

Note: Submissions which do not follow the above instructions will be rejected. Please make sure you use the sample theme and csv file as instructed above.

**Features:**

- [x] Collections List that displays variants as products


Getting started
---------------------
*Make sure to update **Theme IDs** in config file upon version changes!*

----
#### Workflow
Work cycle should go as follows:
- make changes in development theme:

    `$ npm run dev`
  - if a feature or ongoing iteration needed, stash and create branch. Commit changes in branch to swap between theme and new branch:

    `$ git stash branch <branchname> [<stash>]`

  Commit individual files to repo while in development.
  Once complete, push individual files to production:

    `$ theme deploy <filename> <filename> --env=production`

  Check production in browser for changes, making sure development preview is turned off.

----


### Development
`$ npm run dev`

### Production
To deploy approved and checked-in development files to production:

`$ theme deploy <filename> <filename> --env=production`

To deploy files to prod, run (USE WITH CAUTION):
`$ npm run prod`



Additional resources
---------------------
- [Shopify Liquid Cheat Sheet](https://www.shopify.com/partners/shopify-cheat-sheet)

Disclaimer
---------------------
