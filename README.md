Create `sql` file in `init` folder with any name, write any init code, for example:
```sql
CREATE DATABASE IF NOT EXISTS `gitea`;

CREATE USER IF NOT EXISTS 'gitea'@'%' IDENTIFIED BY 'password';
GRANT ALL ON `gitea`.* TO 'gitea'@'%';


CREATE DATABASE IF NOT EXISTS `nextcloud`;

CREATE USER IF NOT EXISTS 'nextcloud'@'%' IDENTIFIED BY 'password';
GRANT ALL ON `nextcloud`.* TO 'nextcloud'@'%';


CREATE DATABASE IF NOT EXISTS vaultwarden;

CREATE USER IF NOT EXISTS 'vw'@'%' IDENTIFIED BY 'password'; 
GRANT ALL ON vaultwarden.* TO 'vw'@'%';
```
