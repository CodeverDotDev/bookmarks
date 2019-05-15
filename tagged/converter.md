##Bookmarks tagged [[converter]](https://www.bookmarks.dev?q=[converter])

_<sup><sup>[www.bookmarks.dev/tagged/converter](https://www.bookmarks.dev/tagged/converter)</sup></sup>_
---
#### [How to convert milliseconds to date string in Oracle SQL](http://www.asjava.com/oracle/how-to-convert-milliseconds-to-date-string-in-oracle-sql/)
_<sup>http://www.asjava.com/oracle/how-to-convert-milliseconds-to-date-string-in-oracle-sql/</sup>_

```
select to_char(to_date('1970-01-01 00','yyyy-mm-dd hh24') +
(1126483200000)/1000/60/60/24 , 'YYYY-MM-DD HH12:MI:SS am') datestr from dual
```
where `1126483200000` is the time in milliseconds. 
* **tags**: [oracle](../tagged/oracle.md), [converter](../tagged/converter.md)
---
