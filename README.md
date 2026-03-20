# AutoMySQLBackup / AutoMariaDBBackup

Minimalistyczny fork **AutoMySQLBackup**, utrzymywany w dwóch wariantach:

- **AutoMySQLBackup** – MySQL (mysqldump)
- **AutoMariaDBBackup** – MariaDB (mariadb-dump / mysqldump)

Projekt skupia się wyłącznie na **logicznym backupie baz danych (SQL dump)**:
- każda baza zapisywana do osobnego pliku `.sql.gz`
- wsparcie dla InnoDB i MyISAM
- backup możliwy do odtworzenia na innej maszynie

Repozytorium celowo pozostaje **proste i czytelne**:
- dwa niezależne skrypty
- dwa niezależne instalatory
- brak zbędnej dokumentacji i teorii