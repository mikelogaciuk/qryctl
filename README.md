# qryctl

## About

Dummy SQL query tool.

## Usage

```shell
git clone https://github.com/mikelogaciuk/qryctl.git && cd qryctl
```

```shell
$ ./qryctl get 'dwh.company.local' 'staging' 'SELECT TOP 5 store, sale_id, sale_date FROM dbo.Sales'

STORE  | SALE_DATE  | SALE_ID
-------|------------|-------------
91094  | 2013-10-14 | 709391160738
188343 | 2014-11-14 | 775295660268
188343 | 2014-11-14 | 775295991936
188343 | 2014-11-14 | 775296592335
188343 | 2014-11-14 | 775296601326
```
