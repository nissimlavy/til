#Getting the distinct values of multiple columns

``` sql
	SELECT DISTINCT a,b,c FROM t
```

is roughly equivalent to:

```sql
SELECT a,b,c FROM t GROUP BY a,b,c
```
