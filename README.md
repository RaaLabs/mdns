# mdns

mdns server

## How to start mdns

```bash
./mdns --help
Usage of ./mdns:
  -fileName string
    specify the json filename from where to read the config (default "./recordsA.json")
```

## Example of json config file

```json
{
    "records": [
        {
            "name":"ws.local",
            "ip":"10.0.0.2",
            "ttl":"60"
        },
        {
            "name":"router.local",
            "ip":"10.0.0.1",
            "ttl":"60"
        },
        {
            "name":"nas.local",
            "ip":"10.0.0.3",
            "ttl":"60"
        }
    ]
}
```
