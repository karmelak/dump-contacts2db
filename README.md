## dump-contacts2db.sh
Dumps contacts from an Android contacts2.db to stdout in vCard format.

### Usage 
```Bash
dump-contacts2db.sh path/to/contacts2.db > path/to/output-file.vcf
```

### Dependencies
* perl
* base64
* sqlite3 / libsqlite3-dev

### Tested platforms
* Ubuntu 12.04 Precise Pangolin

### Tested Android versions (all Google Experience Devices)
* 2.3.5 Gingerbread
* 4.0.3 Ice Cream Sandwich
* 4.1.1 Jelly Bean

### Known issues
* Doesn't handle file-not-found or type mismatch gracefully; need to implement validation
* Doesn't handle missing sqlite gracefully; need to implement validation



