=== Currency Converter Calculator ===
Contributors: falselight
Tags: currency converter, currency conversion, currency calculator, exchange rates, forex
Donate link: https://currencyrate.today/converter-widget
Requires at least: 3.1
Tested up to: 7.1
Requires PHP: 5.3
Stable tag: 1.4.3
License: GPLv2 or later
License URI: https://www.gnu.org/licenses/gpl-2.0.html

Beautiful live currency converter for 190+ currencies, crypto, and metals. No API key needed.

== Description ==

Currency Converter Calculator helps visitors convert prices and amounts without leaving your page.
Add live currency conversion to pricing pages, tourism and travel guides, news websites, finance articles, business pages, and sidebars with a shortcode or classic widget.

Visitors get instant currency context in the place where they are already reading, shopping, comparing, or planning.
Site owners get a lightweight setup: no API key, no local rate database, and no exchange-rate processing load on WordPress.

= ⭐ What makes it useful =

* 🌍 190+ currencies and assets, including popular cryptocurrencies and metals.
* 💱 Live currency conversion directly inside posts, pages, sidebars, and footers.
* 🧩 Add the converter with a shortcode, the Shortcode block, or a classic WordPress widget.
* ⚡ No API key, local exchange-rate database, or exchange-rate processing load on your WordPress site.
* 📱 Responsive layout for desktop and mobile visitors.
* 🎨 Color themes, background color, large mode, and corner style options.
* 🌐 Multilingual widget labels for international audiences.
* 🕒 Time zone setting for the displayed update date.
* 🔒 SSL-ready CurrencyRate.Today service URLs.

= 🎯 Where it works best =

* Pricing pages where visitors need to understand a price in their own currency.
* Tourism and travel websites where readers estimate trip costs.
* News websites that cover markets, business, inflation, travel, or international stories.
* Finance blogs that need a simple converter next to rate commentary.
* Business and service pages for international customers.
* Multilingual sites that need converter labels in the visitor's language.

= 👀 Demos =

* Official demo: [Currency Converter Widget](https://currencyrate.today/converter-widget)
* Product demo: [Currency Converter Calculator](https://yuri.ws/currency-converter-calculator/)

= 🚀 Quick start =

1. Install and activate Currency Converter Calculator.
2. Paste the shortcode into a post, page, or Shortcode block.
3. Choose the source currency, target currency, language, theme, background, and layout.
4. Optionally add the classic widget to a sidebar or footer.

Important: this plugin provides a classic `WP_Widget`.
On modern WordPress installations with the block-based widget screen, install and activate Classic Widgets to manage the widget in Appearance > Widgets.
Shortcodes work without Classic Widgets.

= 🧩 Shortcode examples =

Pricing converter example:

`[ccc_currency_converter_calculator lg="en" tz="0" fm="EUR" to="USD" st="info" bg="FFFFFF" lr="1" rd="0" size_width="100%"][/ccc_currency_converter_calculator]`

Travel converter example:

`[ccc_currency_converter_calculator lg="en" tz="0" fm="USD" to="EUR" st="success" bg="FFFFFF" lr="0" rd="0" size_width="100%"][/ccc_currency_converter_calculator]`

= 🔧 Shortcode attributes =

* `lg` - language. Supported values: `en`, `ru`, `it`, `fr`, `es`, `de`, `cn`, `pt`, `ja`, `id`, `hi`.
* `tz` - time zone offset.
* `fm` - source currency code, for example `EUR`.
* `to` - target currency code, for example `USD`.
* `st` - theme. Supported values: `primary`, `info`, `danger`, `warning`, `gray`, `success`.
* `bg` - widget background color when rounded corners are enabled, for example `FFFFFF`.
* `lr` - large widget mode. Use `1` to enable it or `0` to disable it.
* `rd` - straight corners. Use `1` for straight corners or `0` for rounded corners.
* `size_width` - widget width, for example `100%`.

Currency codes are listed at [https://currencyrate.today/different-currencies](https://currencyrate.today/different-currencies).

== Installation ==

= From your WordPress dashboard =

1. Go to Plugins > Add New.
2. Search for "Currency Converter Calculator".
3. Install and activate the plugin.
4. Add the shortcode to a page or post, or add the classic widget under Appearance > Widgets.

= From WordPress.org =

1. Download Currency Converter Calculator.
2. Upload the `currency-converter-calculator` folder to `/wp-content/plugins/`.
3. Activate the plugin from Plugins > Installed Plugins.
4. Add the shortcode to a page or post, or add the classic widget under Appearance > Widgets.

= Classic widget setup =

1. Install and activate the [Classic Widgets plugin](https://wordpress.org/plugins/classic-widgets/) if your site uses the block-based widget screen.
2. Go to Appearance > Widgets.
3. Add "Currency Converter Calculator" to a widget area.
4. Choose currencies, language, theme, and display options, then save.

== Frequently Asked Questions ==

= How do I add the converter to a page or post? =

Use a shortcode or paste it into a Shortcode block:

`[ccc_currency_converter_calculator lg="en" tz="0" fm="EUR" to="USD" st="info" bg="FFFFFF" lr="1" rd="0" size_width="100%"][/ccc_currency_converter_calculator]`

= Can I show the converter in a sidebar? =

Yes. Add "Currency Converter Calculator" under Appearance > Widgets.
If your WordPress site uses the block-based widget screen, install and activate Classic Widgets first.

= Do visitors leave my website to convert currencies? =

No. The converter is embedded directly on your page, post, sidebar, or footer.

= Does the plugin require an API key? =

No. Exchange-rate lookup and display are handled by the embedded CurrencyRate.Today service, so you do not need an API key or local rate database.

= Can I choose currencies, language, and theme? =

Yes. You can choose the source currency, target currency, language, time zone, color theme, background, size mode, corner style, and width.

= Which shortcode attributes are available? =

The main attributes are `lg`, `tz`, `fm`, `to`, `st`, `bg`, `lr`, `rd`, and `size_width`.
See the shortcode attributes section above for the full list.

= External service and privacy =

Yes. The plugin embeds an iframe from CurrencyRate.Today.
When a page containing the converter is viewed, the visitor's browser requests `https://currencyrate.today/load-converter`.

The request includes display settings such as source currency, target currency, language, theme, time zone, background color, and widget size.
These values come from the shortcode or widget settings.

The plugin does not send WordPress usernames, passwords, admin settings, or private site data to the service.

Service provider: CurrencyRate.Today

* Service website: [https://currencyrate.today/](https://currencyrate.today/)
* Privacy policy: [https://currencyrate.today/page/privacy](https://currencyrate.today/page/privacy)
* Disclaimer: [https://currencyrate.today/page/disclaimer](https://currencyrate.today/page/disclaimer)

= Does the plugin include a Gutenberg block? =

No. The plugin currently supports shortcodes and classic widgets. In the block editor, use a Shortcode block.

== Screenshots ==

1. screenshot-1.jpg: Widget settings.
2. screenshot-2.png: Gray theme.
3. screenshot-3.png: Red theme.
4. screenshot-4.png: Yellow theme.
5. screenshot-5.png: Blue theme.
6. screenshot-6.png: Dark blue theme.
7. screenshot-7.png: Green theme.

== Upgrade Notice ==

= 1.4.3 =
Verified compatibility with WordPress 7.1. Fixed the background color picker not initializing in the block-based widgets editor. Existing shortcodes and classic widget settings continue to work.

== Changelog ==

= 1.4.3 =
* Verified compatibility with WordPress 7.1.
* Fixed color picker (jscolor) initialization in the block-based widgets editor: the picker now initializes when the color field is focused.

= 1.4.2 =
* Verified WordPress 7 compatibility with Classic Widgets.
* Improved PHP 8.x runtime safety for shortcode and classic widget handling.
* Cleaned up plugin metadata, readme wording, and installation instructions.

= 1.4.1 =
* Minor bug fixed.

= 1.4.0 =
* Fixed security bugs.
* Minor bug fixed.
* Added language POT file.

= 1.3.2 =
* Fixed security bugs.
* Minor bug fixed.

= 1.3.1 =
* Added Binance Coin.
* Minor bug fixed.

= 1.3.0 =
* Minor bug fixed.
* Added accessibility improvements.

= 1.2.2 =
* Important fix.
* Minor fix.

= 1.2.0 =
* Minor bug fixed.

= 1.1.0 =
* Added new languages: Portuguese, Japanese, Bahasa Indonesia, and Hindi.

= 1.0.2 =
* Minor bug fixed.

= 1.0.1 =
* Fixed generated shortcode parameters with empty values.

= 1.0.0 =
* First release.

== Donations ==

Official website and data source: [CurrencyRate.Today](https://currencyrate.today/)

You may also like these plugins:

* [Crypto Converter ⚡ Widget](https://wordpress.org/plugins/crypto-converter-widget/)
* [Cryptocurrency Price Widget](https://wordpress.org/plugins/cryptocurrency-price-widget/)
* [Currency Converter Calculator](https://wordpress.org/plugins/currency-converter-calculator/)
* [Currency Converter Widget ⚡ PRO](https://wordpress.org/plugins/currency-converter-widget-pro/)
* [CurrencyRate.Today - Currency Blocks and Widgets](https://wordpress.org/plugins/currencyrate-today-currency-blocks/)
* [Exchange Rates](https://wordpress.org/plugins/exchange-rates/)
* [Exchange Rates Widget](https://wordpress.org/plugins/exchange-rates-widget/)
* [FX Currency Converter](https://wordpress.org/plugins/fx-currency-converter/)
