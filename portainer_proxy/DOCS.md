This addon creates a proxy to a Portainer server run separately from Home Assistant so that you can have the benefit of access in the sidebar without running Portainer as an addon.

Note that this addon does not run Portainer itself.

## Configuration

### Option: `server`

The `server` option sets the address of the Portainer server.

This must be in the format `host:port`. The following are valid examples:

- `portainer.local:9000`
- `192.168.0.101:9000`

## Required Dependencies
- Network access to running Portainer server
