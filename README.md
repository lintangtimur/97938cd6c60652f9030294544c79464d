# SQL - Mini Project

### Milestone 3
Query dibawah ini ada di file dump juga, bagian bawah


```sql
INSERT INTO actors (id, username, password, role_id, verified, active, created_at, updated_at)
VALUES (1, 'superadmin', 'password', 1, 'true', 'true', NOW(), NOW());

CREATE USER 'superadmin'@'0.0.0.0' IDENTIFIED BY 'password';
GRANT ALL PRIVILEGES ON tugas.* TO 'superadmin'@'0.0.0.0';
```
