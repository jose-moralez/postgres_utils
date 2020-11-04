# Postgres utils
> Utilities for interacting with postgresql databases using credentials from .env files.


## Install

`pip install postgres-utils`

## How to use

Set up a `.env` file using the following names for the credentials:

```
POSTGRES_HOST_{SERVER} =
POSTGRES_PORT_{SERVER} =
POSTGRES_DATABASE_{SERVER} =
POSTGRES_USER_{SERVER} =
POSTGRES_PASSWORD_{SERVER} =
```

Then you can create a connection to that server with the following:

```
con = create_connection('server', '.env')
```
