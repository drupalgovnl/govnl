# GovNL Drupal Distribution

Drupal Distribution and install profile to create a Drupal website for the
Dutch government.

## Getting started

Create a new project using a composer template.

Change `PROJECT_NAME` to the name of your project.

```
composer create-project drupalgovnl/govnl_project PROJECT_NAME -s dev --no-install
```
## Information

This profile will install the following modules & themes. Along with a set of config which serves as a basis for Dutch government drupal sites.

### Core

  - automated_cron
  - breakpoint
  - block
  - block_content
  - ckeditor5
  - config
  - contextual
  - datetime
  - dblog
  - dynamic_page_cache
  - editor
  - field_ui
  - file
  - help
  - history
  - image
  - node
  - menu_link_content
  - menu_ui
  - options
  - page_cache
  - path
  - quickedit
  - taxonomy
  - toolbar
  - views
  - views_ui

### Contrib

  - admin_toolbar
  - admin_toolbar_tools
  - entity_browser
  - field_group
  - token
  - pathauto
  - metatag
  - chosen
  - redirect
  - role_delegation
  - username_enumeration_prevention
  - disable_user_1_edit
  - rabbit_hole
  - seckit
  - remove_http_headers

### Themes (admin)

  - claro

### Configuration

    This profile comes with default configuration for basic_html and full_html editor formats. A default pathauto pattern, basic seckit and remove_http_headers settings.
