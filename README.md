# D&D Module Generator

A PHP-based tool for generating random D&D adventure modules, NPCs, villains, settlements, and locales. Built to speed up DM prep time from hours to minutes.

## Features

- **Adventure Generator** - Creates complete adventure outlines with patrons, villains, goals, complications, twists, and climaxes
- **NPC Generator** - Generates NPCs with appearance, abilities, talents, mannerisms, and backstory elements
- **Villain Generator** - Creates villains with schemes, methods, actions, and weaknesses
- **Settlement Generator** - Generates settlements with rulers, features, and current events
- **Locale Generator** - Creates locales with odd features and strange characteristics

## Requirements

- PHP 7.4+
- Web server (Apache/Nginx) or PHP built-in server

## Installation

```bash
git clone https://github.com/itsdarklikehell/dndmodulegenerator.git
cd dndmodulegenerator
```

## Usage

### Web Interface

Place the `site/` directory in your web server's document root and navigate to it:

```bash
# Using PHP built-in server
cd site
php -S localhost:8000
```

Then open http://localhost:8000 in your browser.

### CLI

```bash
php basicGenerator.php
```

## Project Structure

- `site/` - Web interface
  - `adventureGenerator/` - Adventure generation
  - `npcGenerator/` - NPC generation
  - `villainGenerator/` - Villain generation
  - `settlementGenerator/` - Settlement generation
  - `localeGenerator/` - Locale generation
- `lists/` - Data lists for generators
- `raw lists/` - Raw data lists
- `outputScripts/` - Example output

## License

MIT
