postgresql-backup-restore-scripts
=================================

PostgreSQL backup and restore shell scripts

Usage examples
--------------

You can just run the scripts without parameters, and then input the params:

    $ sh pgsql_backup.sh
    
    $ sh pgsql_restore.sh

Or, you can run the script with all the params:

    $ sh pgsql_backup.sh postgres mydb mydb.schema.sql mydb.data.sql --exclude-schema=audit

    $ sh pgsql_restore.sh testuser testdb mydb.schema.sql mydb.data.sql
