# Habari Plugin Directory
## Purpose
This is a plugin which permit Habari to connect distant and multiples web services.

## Configuration
```json
{
  "connectionType": "com.qazima.habari.plugin.webservices.Plugin",
  "metadataUri": "^/metadata.*",
  "uri": "(^api/ws)(.*)"
}
```
