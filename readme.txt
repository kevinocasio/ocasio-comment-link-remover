=== Ocasio Comment Link Remover ===
Contributors: ocas
Tags: comment links, spam remover, comment form, backlink spam, comments
Requires at least: 6.0
Tested up to: 6.7
Stable tag: 1.0.0
Requires PHP: 7.4
License: GPLv2 or later
License URI: https://www.gnu.org/licenses/gpl-2.0.html

Strips author website links and URLs from WordPress comments to eliminate backlink spam.

== Description ==

Spammers target WordPress blogs for one reason: to drop low-quality backlink URLs in the comment form. Moderating hundreds of spam comments wastes hours of your week and clutters your database.

Ocasio Comment Link Remover shuts this down at the source. It removes the "Website" URL field from your public comment form, removing the incentive for spammers to post on your articles. It also strips the clickable link from existing comment author names so your site never passes SEO link juice to spam websites.

Legitimate readers can still leave their name and thoughtful comments, while automated bots and link farmers move on.

= Features =

* **Removes Website URL Field:** Hides the website input box from your WordPress comment form.
* **Author Link Stripper:** Unlinks comment author names so spam bots get zero backlinks.
* **Clean Cookie Consent:** Updates cookie consent text to remove mentions of website fields.
* **Zero Front-End Assets:** Pure PHP execution with 0 bytes of extra CSS or JavaScript.
* **Instant Dashboard Switch:** Turn the feature on or off in one click directly from the Ocasio Plugins dashboard.

== Installation ==

1. Upload the `ocasio-comment-link-remover` folder to your `/wp-content/plugins/` directory, or install it directly through the WordPress plugins screen.
2. Activate the plugin through the 'Plugins' screen in WordPress.
3. Go to **Ocasio Plugins -> Dashboard** in your sidebar to toggle your settings.

== Frequently Asked Questions ==

= Can visitors still leave their name and email? =
Yes. The name and email fields remain active so legitimate visitors can comment normally.

= Will this slow down my website? =
No. The plugin uses lightweight WordPress PHP filters and doesn't load extra CSS or JS files.

== Changelog ==

= 1.0.0 =
* Initial public release.
