## kvdictl users update

Update VDI users

```
kvdictl users update [USER] [flags]
```

### Options

```
      --generate-password     generate a new password to replace the existing one with
  -h, --help                  help for update
      --password string       update the password for the user
      --password-length int   the length to use when generating passwords (default 16)
      --roles strings         update the roles for the user
```

### Options inherited from parent commands

```
  -C, --ca-file string         the CA certificate to use to verify the API certificate
  -c, --config string          configuration file (default "$HOME/.kvdi.yaml")
  -f, --filter string          a jmespath expression for filtering results (where applicable)
  -k, --insecure-skip-verify   skip verification of the API server certificate
  -o, --output string          the format to dump results in (default "json")
  -s, --server string          the address to the kvdi API server (default "https://127.0.0.1")
  -u, --user string            the username to use when authenticating against the API (default "admin")
```

### SEE ALSO

* [kvdictl users](kvdictl_users.md)	 - Users commands

###### Auto generated by spf13/cobra on 14-Aug-2021
