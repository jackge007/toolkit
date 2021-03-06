## tk export source helm

Export HelmRepository sources in YAML format

### Synopsis

The export source git command exports on or all HelmRepository sources in YAML format.

```
tk export source helm [name] [flags]
```

### Examples

```
  # Export all HelmRepository sources
  tk export source helm --all > sources.yaml

  # Export a HelmRepository source including the basic auth credentials
  tk export source helm my-private-repo --with-credentials > source.yaml

```

### Options

```
  -h, --help   help for helm
```

### Options inherited from parent commands

```
      --all                 select all resources
      --kubeconfig string   path to the kubeconfig file (default "~/.kube/config")
      --namespace string    the namespace scope for this operation (default "gitops-system")
      --timeout duration    timeout for this operation (default 5m0s)
      --verbose             print generated objects
      --with-credentials    include credential secrets
```

### SEE ALSO

* [tk export source](tk_export_source.md)	 - Export sources

