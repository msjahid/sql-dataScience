# sql-dataScience

Basic Command

```sudo -i -u postgres```

Create user

```CREATE USER <username> WITH ENCRYPTED PASSWORD <'password'>;```

pgcli connect 

```pgcli -h localhost -U <username> -W <'password'> -d <database_name>```

Create databases for particular user
```bash
sudo -i -u postgres
createdb <databasename> -O <username>
```

Create Interactive user with role

```createuser --interactive -P```
