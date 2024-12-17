## PHP Microsoft Teams Connector

This is a fork of Sebastian Bretschneider's [PHP Microsoft Teams Connector] (https://github.com/sebbmeyer/php-microsoft-teams-connector) with a couple of updates to ensure compatibility with Microsoft's [Power Automate](https://www.microsoft.com/en-us/power-platform/products/power-automate):

- [Cast version to string](https://github.com/testmonitor/php-microsoft-teams-connector/commit/a7271b623165bd8edff368d345b5a99ea21ded7b)
- [Allow empty results for Power Automate](https://github.com/testmonitor/php-microsoft-teams-connector/commit/836ff4390776a265c316bea697a5ad15d4f159c7)

## Installation

You can install the package via composer:

```bash
composer require testmonitor/php-microsoft-teams-connector
```

## Usage

Please refer to the [documentation](https://github.com/sebbmeyer/php-microsoft-teams-connector?tab=readme-ov-file#usage)
of the original package.

## Testing

The test setup is very basic at the moment. There is only one test script available right now.

### Prerequisites

- PHP
- Composer

### Run tests
- Run `composer install`
- Duplicate `.env.example` and rename it to `.env`
- Add Incoming Webhook url to the `.env` file variable **INCOMING_WEBHOOK**
- Execute script with `php tests/full_width.php`

## License

This PHP Microsoft Teams connector is open-sourced software licensed under the [MIT license](http://opensource.org/licenses/MIT)
