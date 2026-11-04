# ChargingNear.me for Cursor

Search U.S. EV charging stations from Cursor: nearest chargers, stations along a route, city and state stats, highway charging gaps and NEVI status. Read-only.

## Install

Install from the Cursor Marketplace, or add this to your Cursor MCP settings:

```json
{
  "mcpServers": {
    "chargingnear-me": {
      "url": "https://chargingnear.me/api/mcp"
    }
  }
}
```

No API key or configuration is needed. Signing in is optional and only adds the three `get_my_*` tools.

## Tools

- `search_stations`: Search by city, state, network, connector, speed or live availability
- `get_nearest_stations`: Nearest stations to a point
- `get_station_details`: Details for one station
- `get_city_charging_stats`: City charging statistics
- `get_state_charging_stats`: State charging statistics
- `get_catalog_totals`: Live size of the national catalog
- `find_stations_on_route`: Stations along a route
- `get_charging_gaps`: Highway charging gaps
- `get_corridor_chargers`: Fast chargers on a corridor in driving order
- `get_nevi_status`: Stations meeting federal NEVI minimums
- `get_my_saved_stations`, `get_my_trips`, `get_my_alerts`: The user's own saved stations, trips and alerts (optional OAuth sign-in)

## Example prompts

- "Find DC fast chargers within 10 miles of Vail, CO"
- "Which fast chargers are along I-70 from Denver to Grand Junction?"
- "How many charging locations does Texas have, by network?"

## Links

- Docs: https://chargingnear.me/mcp
- Server: https://chargingnear.me/api/mcp

Maintained by Wins Parking, LLC.
