# ftpasswd

## ftpasswd.dist : using demo account

- copy `ftpasswd.dist` to `ftpasswd`
- user provided is `demo` with password `demo`

## create your own : account

- copy `ftpasswd.dist` to `ftpasswd`
- run the `ftpasswd`command (either from another linux system or from the container itself using `docker run -it webofmars/joomla:latest bash`)
- run the following command : `ftpasswd --passwd --file - --name demo --home /var/empty --shell /bin/nologin --uid 65564 --gid 65564`
- copy the output line to `ftpasswd` file

