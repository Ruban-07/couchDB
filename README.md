# CouchDB
![Couch logo](couch.png)
CouchDB uses views as the primary tool for running queries and creating reports from stored document files. Views allow you to filter documents to find information relevant to a particular database process. This information can then be mapped according to your preferences and extracted in a specific order.

## Installation :
Please run the below commands step by step to install couchDB in `UBUNTU`

**Installation command**
```dart
$ sudo snap install couchdb
```

**Couch Status**
```dart
$ couchdb
```

**Setup Admin Password**
```dart
$ sudo snap set couchdb admin=*******
```

**Start couchDB Server**
```dart
$ sudo snap start couchdb
```

**Observe when to initiate cleanup**
```dart
$ sudo snap connect couchdb:mount-observe
```

**indexer to set the priority of couchjs**
```dart
$ sudo snap connect couchdb:process-control
```

**Finally run this URL & login to your DB as `Admin`**
```dart
$ http://127.0.0.1:5984/_utils/#login
```