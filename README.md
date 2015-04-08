#U-Wheel
Uninventing the wheel

##Overview
uw wraps the drivers for popular database engines, providing a *promise-way* and an unified method to interact.

##Database Engines supported
* mssql
* pg
* sqlite

##Install
```bash
npm install uw --save
```

##Config
The ```config.json``` sets the necessary data for each engine:
```javascript
database {
  ip: localhost, // unused on sqlite
  user: 'root', // unused on sqlite
  password: 'root', // unused on sqlite
  dbname: 'my_db', // a path on sqlite, or ':memory:'
  type: 'pg' // pg (default) | sqlserver | sqlite
}
```

This file is located on ```.../config/uw``` by definition

##Examples
