# Gateway

An ingress Gateway describes a load balancer operating at the edge of the mesh that receives incoming HTTP/TCP connections. 

## Usage

Command to install Gateway:

```
helm upgrade -i api-ingress-gateway . -n istio-system --values=config/api-gateway.yaml
```
