# Destination Rules

DestinationRule defines policies that apply to traffic intended for a service after routing has occurred.

## Usage

Sample command to install a Destination Rule:

```
helm upgrade -i <service_name>-destination-rule . -n pes-2-0 --values=apps/<env>/<service_name>.yaml
```