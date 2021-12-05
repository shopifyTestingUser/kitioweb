# Impulse - template shopify

### Before you start
* Install Ruby https://www.ruby-lang.org/en/.
* If you want to use a development store https://shopify.dev/themes/tools/development-stores to build a theme, then create or log in to a Shopify Partner account https://partners.shopify.com/signup?shpxid=940cdcb5-0E86-46F0-A4E7-5D1F035D35DB , and then create a development store https://shopify.dev/themes/tools/development-stores#development-store-apps-themes.
* Make sure that you have a collaborator account https://shopify.dev/themes/tools/collaborator-accounts or a staff account https://help.shopify.com/manual/your-account/staff-accounts?shpxid=940cdcb5-0E86-46F0-A4E7-5D1F035D35DB with the Manage themes permission or Themes permission for the store that you want to work on, or you're the owner of the store.
* Note the URL of the store that you want to work on.
* Make sure that you're connected to the internet. Most Shopify CLI commands need an internet connection to run.

### Installation Shopify CLI:

* Download the latest version of the shopify-cli-x.y.z.deb file: https://github.com/Shopify/shopify-cli/releases
* ```sudo apt install /path/to/download/shopify-cli-x.y.z.deb``` - install Shopify CLI
* To verify that Shopify CLI is installed properly, run the following command: ```shopify version```

### Preview, test, and share your theme
* To serve your theme, run the following command: ``` shopify theme serve ```

#### Shopify CLI uploads the theme as a development theme on the store that you're connected to, and returns the following:

* A link to your development theme at http://127.0.0.1:9292. This URL hot reloads local changes to CSS and sections, allowing you to preview changes in real time using the store's data. This preview is available only in Google Chrome.
* A link to the online store editor for the theme.
* A preview link that you can share with others.

### Customize a theme
* ```shopify login --store [your-domain].myshopify.com``` - : Authenticate with Shopify CLI. In your browser window, log into the account that's attached to the store that you want to use for development.
* ```shopify theme pull ``` - The ability to choose the theme you want to download


## Docs

* Docs - https://shopify.dev/

* Build Shopify themes - https://shopify.dev/themes

* Shopify API reference docs - https://shopify.dev/api

* Theme commands - https://shopify.dev/themes/tools/cli/theme-commands

* Liquid reference - https://shopify.dev/api/liquid

* Liquid phpStorm - https://www.jetbrains.com/help/phpstorm/liquid.html

