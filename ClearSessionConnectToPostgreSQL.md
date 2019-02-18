### To close all of current connection to PostgreSQL

Using query command:

```
SELECT pg_terminate_backend(pg_stat_activity.pid)
FROM pg_stat_activity
WHERE pg_stat_activity.datname = ‘Database Name’
AND pid <> pg_backend_pid();
```
or 

```
SELECT pg_terminate_backend(pid)
FROM pg_stat_get_activity(NULL::integer)
WHERE datid=(SELECT oid from pg_database where datname = ‘Database Name’)
```
=======================================================================================
