---
title: "pgo_create_namespace"
---
## pgo create namespace

Create a namespace

### Synopsis

Create a namespace. For example:

	pgo create namespace somenamespace
	
	Note: For Kubernetes versions prior to 1.12, this command will not function properly - use $PGOROOT/deploy/add_targted_namespace.sh script. For more details, see the Namespace Creation section under Installing Operator Using Bash in the documentation.

```
pgo create namespace [flags]
```

### Options

```
  -h, --help   help for namespace
```

### Options inherited from parent commands

```
      --apiserver-url string     The URL for the PostgreSQL Operator apiserver.
      --debug                    Enable debugging when true.
  -n, --namespace string         The namespace to use for pgo requests.
      --pgo-ca-cert string       The CA Certificate file path for authenticating to the PostgreSQL Operator apiserver.
      --pgo-client-cert string   The Client Certificate file path for authenticating to the PostgreSQL Operator apiserver.
      --pgo-client-key string    The Client Key file path for authenticating to the PostgreSQL Operator apiserver.
```

### SEE ALSO

* [pgo create](/operatorcli/cli/pgo_create/)	 - Create a Postgres Operator resource

###### Auto generated by spf13/cobra on 16-Sep-2019