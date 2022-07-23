# Service Entry

ServiceEntry enables adding additional entries into Istio’s internal service registry, so that auto-discovered services in the mesh can access/route to these manually specified services.

## Usage

Command to install ES Service Entries:

```
helm upgrade -i service-entries . -n istio-system --values=apps/external.yaml
```
