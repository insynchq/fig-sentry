Fig environment for Sentry

```bash
$ fig run --rm sentry sentry --config=/etc/sentry.conf.py upgrade

# create a new user
$ fig run --rm sentry sentry --config=/etc/sentry.conf.py createsuperuser

# run the automated repair script
$ fig run --rm sentry sentry --config=/etc/sentry.conf.py repair --owner=<username>
```
