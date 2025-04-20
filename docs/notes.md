## Open Questions

- Should we use Redis for matchmaking queues?

## Current Assumptions

- Ladder will support only 1v1 at launch
- We will have our own ELO/MMR system for matchmaking


## Random Research

 - [This](https://github.com/Blizzard/s2client-proto/blob/master/docs/protocol.md#play-two-bots-against-each-other) seems to be very close to what needs to be implmented for the ladder matching functionality.
 - Going to have to figure out how to download ladder `.SC2Map` files.  Seems like the way the game downloads them for ladder caches them in an encrypted format that is not useful for our purposes.  Perhaps a way is to extract them from `.SC2Replay` files and package them for distribution with the OpenCraft client.
