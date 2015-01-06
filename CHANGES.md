See the [documentation](http://bkayser.github.io/cleansweep) for details

### Version 1.0.4
* Print dry run output using the logger
* Add option `non_traversing` so you can explicitly not use an index.  If an index
  is not specified, now it will guess using the first non-unique index or primary key.
* Added more tests

### Version 1.0.3

* Small bug in instrumentation and target model reference
* Support first unique index as primary when primary key not found

### Version 1.0.2

* Changed destination options so you can delete from a different table.
* Added `dest_columns` option as a map of column names in the source to column names in the destination.
* More testing and bug fixing in real environments

### Version 1.0.1

* Initial release

