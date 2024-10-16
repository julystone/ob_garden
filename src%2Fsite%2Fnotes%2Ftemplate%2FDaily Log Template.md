```dataview
list
where file.cday = date(<% tp.file.creation_date("YYYY-MM-DD") %>)
sort file.ctime asc
```