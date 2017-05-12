+++
title = "helm test"
weight = "39"

tags = ["commands"]
section = "helm-commands"
categories = ["helm-commands"]
type = "page"

slug = "helm-test"

[menu.main]
  url = "helm-test"
  parent = "helm-commands"

+++

## helm test

test a release

### Synopsis



The test command runs the tests for a release.

The argument this command takes is the name of a deployed release.
The tests to be run are defined in the chart that was installed.


```
helm test [RELEASE]
```

### Options

```
      --cleanup              delete test pods upon completion
      --timeout int          time in seconds to wait for any individual kubernetes operation (like Jobs for hooks) (default 300)
      --tls                  enable TLS for request
      --tls-ca-cert string   path to TLS CA certificate file (default "$HELM_HOME/ca.pem")
      --tls-cert string      path to TLS certificate file (default "$HELM_HOME/cert.pem")
      --tls-key string       path to TLS key file (default "$HELM_HOME/key.pem")
      --tls-verify           enable TLS for request and verify remote
```

### Options inherited from parent commands

```
      --debug                     enable verbose output
      --home string               location of your Helm config. Overrides $HELM_HOME (default "~/.helm")
      --host string               address of tiller. Overrides $HELM_HOST
      --kube-context string       name of the kubeconfig context to use
      --tiller-namespace string   namespace of tiller (default "kube-system")
```

### SEE ALSO
* [helm](#helm)	 - The Helm package manager for Kubernetes.