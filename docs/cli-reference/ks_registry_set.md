## ks registry set

Set configuration options for registry

### Synopsis


The `set` command sets configuration parameters on a configured registry.
The following parameters can be set:

* --uri: The uri a registry points to. For GitHub-based registries, this can be used to select a specific branch.


```
ks registry set [registry-name] [flags]
```

### Examples

```

	# Set the incubator registry to the experimental branch:
	ks registry set incubator --uri https://github.com/ksonnet/parts/tree/experimental/incubator

```

### Options

```
  -h, --help         help for set
      --uri string   URI to configure the registry
```

### Options inherited from parent commands

```
  -v, --verbose count[=-1]   Increase verbosity. May be given multiple times.
```

### SEE ALSO

* [ks registry](ks_registry.md)	 - Manage registries for current project

