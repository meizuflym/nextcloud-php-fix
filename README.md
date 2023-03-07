fix a nextcloud 24/25 php8.2 problem.
move this fix to /nextcloud/lib and restart web server.
this fix removes the php version check and makes the service work with officially incompatible php versions

Фикс для Nextcloud 24/25 убирает проверку версии php и заставляет работать сервис на оффициально несовместимых версиях
для установки замените файл versioncheck.php в папке /nextcloud/lib/ на этот фикс.
