=== Currency Converter Calculator ===
Contributors: falselight
Tags: currency converter, currency conversion, currency calculator, exchange rates, forex
Donate link: https://currencyrate.today/converter-widget
Requires at least: 3.1
Tested up to: 7.0
Requires PHP: 5.3
Stable tag: 1.4.2
License: GPLv2 or later
License URI: https://www.gnu.org/licenses/gpl-2.0.html

Give visitors a fast, responsive currency converter that keeps them on your site without adding exchange-rate load to WordPress.

== Description ==

Currency Converter Calculator adds a responsive CurrencyRate.Today converter to pages, posts, and classic widget areas.
Visitors can compare rates in place while your WordPress site stays light.

The converter is powered by CurrencyRate.Today.
Exchange-rate lookups and rate display happen in the embedded service, so setup stays simple: no API key, no local rate database,
and no exchange-rate processing load on your WordPress site.

Features:

* About 190 currencies and assets, including popular cryptocurrencies and metals.
* Shortcode support for pages, posts, and the Shortcode block.
* Classic WordPress widget support.
* Responsive auto-width iframe layout.
* No API key, local exchange-rate database, or exchange-rate processing load on WordPress.
* Multiple color themes.
* Multilingual widget labels.
* Time zone setting for the displayed update date.
* SSL-ready service URLs.

Important: this plugin provides a classic `WP_Widget`.
On modern WordPress installations with the block-based widget screen, install and activate Classic Widgets to manage the widget in Appearance > Widgets.
Shortcodes work without Classic Widgets.

👀 Demo: [Currency Converter Widget](https://currencyrate.today/converter-widget)
👀 Product demo: [Currency Converter Calculator](https://yuri.ws/currency-converter-calculator/)

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

Use the shortcode:

`[ccc_currency_converter_calculator lg="en" tz="0" fm="EUR" to="USD" st="info" bg="FFFFFF" lr="1" rd="0"][/ccc_currency_converter_calculator]`

You can also paste the shortcode into a Shortcode block in the block editor.

= Which shortcode attributes are available? =

* `lg` - language. Supported values: `en`, `ru`, `it`, `fr`, `es`, `de`, `cn`, `pt`, `ja`, `id`, `hi`.
* `tz` - time zone offset.
* `fm` - source currency code, for example `EUR`.
* `to` - target currency code, for example `USD`.
* `st` - theme. Supported values: `primary`, `info`, `danger`, `warning`, `gray`, `success`.
* `bg` - iframe background color when rounded corners are enabled, for example `FFFFFF`.
* `lr` - large widget mode. Use `1` to enable it or `0` to disable it.
* `rd` - straight corners. Use `1` for straight corners or `0` for rounded corners.
* `size_width` - iframe width, for example `100%`.

Currency codes are listed at [https://currencyrate.today/different-currencies](https://currencyrate.today/different-currencies).

= Does the plugin use an external service? =

Yes. The plugin embeds an iframe from CurrencyRate.Today.

When a page containing the converter is viewed, the visitor's browser requests `https://currencyrate.today/load-converter`.
The request includes display settings such as source currency, target currency, language, theme, time zone, background color, and widget size.
These values come from the shortcode or widget settings.

The plugin does not send WordPress usernames, passwords, admin settings, or private site data to the service.

Service provider: CurrencyRate.Today

* Service website: [https://currencyrate.today/](https://currencyrate.today/)
* Privacy policy: [https://currencyrate.today/page/privacy](https://currencyrate.today/page/privacy)
* Disclaimer: [https://currencyrate.today/page/disclaimer](https://currencyrate.today/page/disclaimer)

= How do I add the converter as a widget? =

Install and activate Classic Widgets if needed, then go to Appearance > Widgets and add "Currency Converter Calculator" to a widget area.

The widget settings screen can also generate a shortcode for the same options.

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

= 1.4.2 =
WordPress 7 compatibility metadata and readme cleanup. Existing shortcodes and classic widget settings continue to work.

== Changelog ==

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
