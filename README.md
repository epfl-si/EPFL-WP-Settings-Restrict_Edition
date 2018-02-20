# EPFL settings: remove capability to add unfiltered html from editors and administrators

## Description

This function removes the capability from adminsitrators and editors to add unfiltered html into WordPress pages

## Base information

|             |                                                          |
| ----------- | -------------------------------------------------------- |
| Plugin Name | Custom restrictions for EPFL                             |
| Plugin URI  | https://github.com/epfl-idevelop/EPFL-WP-Settings-Restrict_Edition| |
| Description | Removes the unfiltered_html and unfiltered_upload capabilities to administrator and editor roles |
| Version     | 0.1.0                                                      |
| Author      | Emmanuel JAEP                                            |
| Author URI  | https://people.epfl.ch/emmanuel.jaep?lang=en             |
| License     | Copyright (c) 2017 Ecole Polytechnique Federale de Lausanne, Switzerland |

## Installation

Simply clone this repository into the ```plugins``` or ```mu-plugins``` directory of WordPress

```bash
cd wp-content/plugins
git clone https://github.com/epfl-idevelop/EPFL-WP-Settings-Restrict_Edition.git
```

## Usage

### Enforcing the restrictions

If placed into the ```mu-plugins``` directory, the restrictions will be enforced every time a user accesses the admin pages of WordPress.

If placed into the ```plugins``` directory, the restrictions will be enforced upon activation of the plugin.

### Removing the restrictions

If placed into the ```mu-plugins``` directory, this plugin should:

- be moved into the ```plugins``` directory
- deactivated

If placed into ```plugins``` directory, simply deactivate the plugin.