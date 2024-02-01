# pgAdmin 4

This service is accessible at http://localhost:5050
(it takes a little while to fully start the service before you can access it)

Once you see the login page on the above URL, login with the credentials that you set for `PGADMIN_DEFAULT_EMAIL` and `PGADMIN_DEFAULT_PASSWORD` in the `compose.yml` file and then follow the steps below to add a new server.

## Add New Server

  1. Click on `Add New Server`

  2. In `General` tab:

      a. Set `Name` to anything (e.g. "localhost")

  3. In `Connection` tab:

      a. Set `Host name/address` to postgres service name (i.e. "postgres") or container name (i.e. "saac-postgres")

      b. Set `Port` to "5432"

      c. Set `Username` to "postgres"

      d. Set `Password` to "root"

  4. Click on `Save`
