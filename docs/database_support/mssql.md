# [Microsoft SQL Server](https://www.microsoft.com/en-us/sql-server/sql-server-2019)
Supported drivers:

| dbapi                              | default    | driver          | connection class              |
|------------------------------------|------------|-----------------|-------------------------------|
| [pymssql](https://www.pymssql.org) | :thumbsup: | `mssql+pymssql` | `pymssql._pymssql.Connection` |

## pymssql
`pymssql` is the default dbapi driver for Microsoft SQL Server in *pydapper*.

### Example - `connect`
Please see the [pymssql docs](https://www.pymssql.org/pymssql_examples.html#using-the-with-statement-context-managers) for
a full description of the context manager behavior.
```python
{!docs/../docs_src/connections/pymssql_connect.py!}
```

### Example - `using`
Use *pydapper* with a custom connection pool.
```python
{!docs/../docs_src/connections/pymssql_using.py!}
```
