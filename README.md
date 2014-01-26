# phileCustomizeLinks

A plugin for PhileCMS to customize links (`a` tags).
Now available:

 * adding rel="nofollow"
 * adding target="_blank"

for external links (which don't contain domain name and don't start with `/`).

### Installation

* Install [Phile](https://github.com/PhileCMS/Phile)
* Clone this repo into `plugins/phileCustomizeLinks`
* add `$config['plugins']['phileCustomizeLinks'] = array('active' => true);` to your `config.php`

### Usage
