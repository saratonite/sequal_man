SQL Add and ALter relation
==========================
```SQL
    `ALTER TABLE  `products_tbl` ADD FOREIGN KEY (  `product_user` ) REFERENCES  `b2b`.`user_tbl` (
`user_id`
) ON DELETE CASCADE ON UPDATE RESTRICT ;`

```

Befor delete
============
```SQL
`ALTER TABLE  `products_tbl` ADD FOREIGN KEY (  `product_user` ) REFERENCES  `b2b`.`user_tbl` (
`user_id`
) ON DELETE CASCADE ON DELETE RESTRICT ;`
```
