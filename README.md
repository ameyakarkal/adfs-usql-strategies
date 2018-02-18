# adfs-usql-strategies
Strategies for Implementing ADFS driven USQL powered ETL lifecycles

These are few strategies of moving data from a transactional database table into your datalake.

#### `Entity`
- table in the transactional database that needs to be moved.

#### `Slice`
- a unit of data of the `Entity` that is moved in a iteration of "copy" process. 
