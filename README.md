# PHP-FPM (php-fpm)

PHP-FPM (FastCGI Process Manager) is the primary PHP FastCGI implementation bundled with PHP for handling heavy-loaded sites, providing advanced process management with multiple worker pools, graceful start/stop, adaptive process spawning (static, dynamic, ondemand), slowlog tracking, and accelerated upload support. It is configured via php.ini-style pool files and is typically deployed behind a web server such as Nginx, Apache, Caddy, or LiteSpeed via FastCGI. PHP-FPM exposes operational status pages (in plain, JSON, XML, OpenMetrics, and HTML formats) but does not provide a public HTTP API; it runs only on POSIX systems that support fork().

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/php-fpm/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/php-fpm/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- PHP
- FastCGI
- Process Manager
- Web Server
- Application Server
- Open Source

## Timestamps

- **Created:** 2026-05-11
- **Modified:** 2026-05-11

## APIs

### PHP-FPM Status Endpoint

Operational status endpoint exposed by PHP-FPM via the pm.status_path directive. Returns pool statistics (active processes, idle processes, accepted connections, slow requests) in plain text, JSON, XML, OpenMetrics, or HTML. There is no public API; the endpoint is served by the local web server through FastCGI on user-defined paths.

- **Human URL:** [https://www.php.net/manual/en/install.fpm.configuration.php](https://www.php.net/manual/en/install.fpm.configuration.php)
- **Base URL:** `http://localhost`

#### Tags

- Status
- Monitoring
- OpenMetrics
- Process Manager

#### Properties

- [Documentation](https://www.php.net/manual/en/install.fpm.php)
- [Configuration](https://www.php.net/manual/en/install.fpm.configuration.php)
- [Installation](https://www.php.net/manual/en/install.fpm.install.php)
- [Postman Collection](collections/php-fpm.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/php-fpm.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Website](https://www.php.net/)
- [Documentation](https://www.php.net/manual/en/install.fpm.php)
- [Download](https://www.php.net/downloads.php)
- [GitHub Repository](https://github.com/php/php-src)
- [Issue  Tracker](https://github.com/php/php-src/issues)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
