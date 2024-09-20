```python
from csv import reader
```


```python
import sqlite3 as sq
```


```python
conn=sq.connect("D:/23bca258/sqlite3/database/stud258.db")
```


```python
cur=conn.cursor()
```


```python
cur.execute("create table if not exists stud123(sid,sname,city,contact)")
```




    <sqlite3.Cursor at 0x60ae5f69d0>




```python
cur.execute("insert into stud123 values(1,'vaikun','valod','7685998765')")
```




    <sqlite3.Cursor at 0x60ae5f69d0>




```python
cur.execute("insert into stud123 values(2,'vicky','bardoli','7685934215')")
```




    <sqlite3.Cursor at 0x60ae5f69d0>




```python
f=open("D:\\23bca258\\sqlite3\\csv\\stud12.csv","r")
```


```python
cur.execute("insert into stud123 values(3,'sai','vyara','7685998675')")
```




    <sqlite3.Cursor at 0x60ae5f69d0>




```python
cur.execute("insert into stud123 values(4,'radhe','bardoli','8185998765')")
```




    <sqlite3.Cursor at 0x60ae5f69d0>




```python
cur.execute("insert into stud123 values(5,'krishn','surat','6755998765')")
```




    <sqlite3.Cursor at 0x60ae5f69d0>




```python
cur.execute("insert into stud123 values(6,'om','bardoli','9185998765')")
```




    <sqlite3.Cursor at 0x60ae5f69d0>




```python
cur.execute("insert into stud123 values(7,'ram','valod','7006598765')")
```




    <sqlite3.Cursor at 0x60ae5f69d0>




```python
cur.execute("insert into stud123 values(8,'govind','bardoli','8085998765')")
```




    <sqlite3.Cursor at 0x60ae5f69d0>




```python
cur.execute("insert into stud123 values(9,'kishori','vapi','9925998765')")
```




    <sqlite3.Cursor at 0x60ae5f69d0>




```python
cur.execute("insert into stud123 values(10,'sita','buhari','7123998765')")
```




    <sqlite3.Cursor at 0x60ae5f69d0>




```python
cur.execute("select * from stud123")
```




    <sqlite3.Cursor at 0x60ae5f69d0>




```python
cur.execute("select * from stud123 where city='bardoli'")
```




    <sqlite3.Cursor at 0x60ae5f69d0>




```python
with open("D:\\23bca258\\sqlite3\\csv\\stud12.csv")as f:r=reader(f)
```


```python
conn=sq.connect("D:\\23bca258\\sqlite3\\csv\\stud12.csv")
```


```python
cur=conn.cursor()
```


```python

```
