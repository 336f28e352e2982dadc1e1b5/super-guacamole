This addon creates a proxy to a Zigbee2mqtt server run separately from Home Assistant so that you can have the benefit of access in the sidebar without running Zigbee2mqtt as an addon.

Note that this addon does not run Zigbee2mqtt itself.

## Configuration

### Option: `server`

The `server` option sets the address of the Zigbee2mqtt server.

This must be in the format `host:port`. The following are valid examples:

- `zigbee2mqtt.local:9999`
- `192.168.0.101:9999`

## Required Dependencies
- Network access to running Zigbee2mqtt server
