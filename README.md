# Helsingborg API Event Manager Integration

This plugin is an LTS version of the Helsingborg Modularity Sections
plugin v3.1.3. It povides graphical sections intended for full-width usage.

## Installation

1. Add the following to your `composer.json` file:
   ```json
   {
     "repositories": [
       {
         "type": "vcs",
         "url": "https://github.com/municipio-lts/wp-plugin-modularity-sections-2024.git",
         "only": [
           "municipio-lts/wp-plugin-modularity-sections-2024"
         ],
         "no-api": true
       },
     ]
   }
   ```
2. Install the package and its dependencies:
   ```bash
   composer require municipio-lts/wp-plugin-modularity-sections-2024:dev-main
   ```
3. Activate the plugin in WordPress.
4. Activate the module under _Modularity → Options_.