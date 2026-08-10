---
title: SQL
tags:
  - programming
  - sql
---

# SQL

## SELECT

```sql
SELECT *
FROM Users;
```

## WHERE

```sql
SELECT *
FROM Users
WHERE Id = 1;
```

## JOIN

```sql
SELECT *
FROM Orders
JOIN Users ON Orders.UserId = Users.Id;
```
