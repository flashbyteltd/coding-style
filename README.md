# Flash Byte Ltd coding style

Stores shared rules for coding style across all projects.

## Usage

### PHP Projects: [Laravel Pint](https://laravel.com/docs/pint)

Note: There should not be a `pint.json` in your project.

1. Install this composer package into the project:
```bash
$ composer require --dev flashbyteltd/coding-style
```

2. Run the `coding-style-init` script:
```bash
$ vendor/bin/coding-style-init
```

3. Run Pint in dry run mode to test it is working correctly:
```bash
$ composer cstest
```

4. Run Pint to test it is working correctly (this will update your PHP files):
```bash
$ composer cs
```
