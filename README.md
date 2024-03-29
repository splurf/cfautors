# cfautors
Automatically updates the path of a [Cloudflare](https://www.cloudflare.com/) DNS record.

## Description
This is a simple workaround for those that don't have an assigned static public IP address. This tool will periodically compare the device's public IP address with the specified DNS record and update the record accordingly using the Cloudflare developer's [API](https://developers.cloudflare.com/api/).

## Usage
```
Usage: cfautors [OPTIONS] --email <EMAIL> --api-token <API_TOKEN> --zone-id <ZONE_ID> --id <ID>

Options:
  -e, --email <EMAIL>          
  -a, --api-token <API_TOKEN>  
  -z, --zone-id <ZONE_ID>      
  -i, --id <ID>                
  -d, --delay <DELAY>          [default: 5min]
  -h, --help                   Print help
  -V, --version                Print version
```

## Todo
+ Allow more than one record at a time.