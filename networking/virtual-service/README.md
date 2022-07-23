# Virtual Services

A VirtualService defines a set of traffic routing rules to apply when a host is addressed. Each routing rule defines matching criteria for traffic of a specific protocol. If the traffic is matched, then it is sent to a named destination service (or subset/version of it) defined in the registry.

## Usage

Sample command to install a VirtualService:

```
helm upgrade -i <service_name>-virtual-service . -n istio-system --values=apps/<stage>/<service_name>.yaml
```
