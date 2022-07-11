# pokedex
A Pokédex implementation.

## Product Requirements
- User can search for a specific pokemon
	- Fuzzy searches should be possible
- User should be able to view pokemon collections grouped by:
	- Number
	- Type
- Indivudal pokemon views should have detailed information
- A user should be able to view pokemon by generation
- Mobile-first
  - Adventurers will most likely not be sitting at a computer when seeing a pokemon in the wild, so the UX should support that
- Make sure data is up-to-date when online
  - Because trainers and adventurers may be traveling through areas with poor service, we may want to pre-fetch data as much as possible so they have access to a wide range of data when they're working offline
  - Client-side DLQ if sorts for attempted messages sent while offline
- Users should be able to mark pokemon as caught

## Ubiquitous Language
- Pokémon
- Type
- Generation
- Ability
- Evolution
