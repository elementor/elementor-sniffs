# Elementor Sniffs

Collection of PHP_CodeSniffer sniffs for Elementor.

## Installation

```php
composer require elementor/elementor-sniffs
```

## Usage

### Command line

```bash
./vendor/bin/phpcs --standard=Elementor-Core <file>
```

### Config file

PHPCS config file:

```xml
<?xml version="1.0"?>
<ruleset name="Elementor Coding Standards">
    <description>My projects ruleset.</description>
    
    <config name="text_domain" value="my-plugin-name" />
        
    <exclude-pattern>vendor/</exclude-pattern>

	<!-- Rules -->
    <rule ref="Elementor-Core" />
</ruleset>
```
