# kubectl-getall
A small kubectl plugin to list all resources in a Kubernetes namespace

## Examples:
- Print all non-empty resources in the current namespace
  ```bash
  kubectl getall
  ```

- Print all resources, including empty, in the current namespace
  ```bash
  kubectl getall -v
  ```

- Print all non-empty resources in the supplied namespace
  ```bash
  kubectl getall kube-system
  ```

- Print all resources, including empty, in the supplied namespace
  ```bash
  kubectl getall -v kube-system
  ```

## Options
-  `-v` List all resources, including empty
  
-  `--help` get some quick help
