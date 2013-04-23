<img src="http://lsauer.github.com/json2sql/res/img/logo_json2sql.png" style="border:0px; margin:10px; margin-right:30px; float:left; zoom:0.5;">


Json2Sql Service Overview
=========================


##### *Json2Sql creates relational databases from your JSON data*

---

**author**: lo sauer 2011-12; www.lsauer.com  
**website**: https://lsauer.github.com/json2sql  
**service**: http://goo.gl/eGdB3  
**license**: MIT or BSD. dual licensed  


**description**: Asynchronous JavaScript and XML (AJAX) has become ubiquitious, and therewith the JSON format with likely over one terrabyte exchanged each day[1]. During application development and during application deployment, it is common routine to access RDBM-Systems, which usually implement SQL (Simple Query Language) as the DML (Data Modeling Language) of choice. This service allows rapid conversion from (most) JSON data-structures to relational SQL, based on a set of empirical heuristics.  

**note**: This is an early version which cannot promise to handle all JSON structures

#### Components


* `PHP-application, database` 

  > `...`
```

#### Features:
- Automatic field-type assignment
- SQL Format conversion
- Modern SQL Format generation / validation
- Drag and Drop- / url- / multiple-local -file or text upload
- Automatic filtering / filter-mapping
- Lightweight, fast code w/o external dependencies
- Accessible as a JSON-RPC or REST web-service

#### Privacy/Other:
- No data is persistently stored on the server, but is stored only in the server's memory for the runtime-duration of the script (~msec). The source code is freely accessible.
- Reverse conversion (`Sql2Json`) is implemented as part of the basic feature set of most popular computer languages.
- Multiple file input is dealt with concatenation

#### Results:
```
...
...
...
```
[1] Assuming 1Billion people, accessing in excees of 1MB of JSON data each day, on average.