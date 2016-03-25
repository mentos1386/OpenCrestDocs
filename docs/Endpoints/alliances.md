## Alliances

`alliances/`

| Route         | Status        |
| ------------- |:-------------:|
| GET           |`Works`|
| POST           |`WIP`|
| PUT           |`WIP`|
| SHOW          |`Works`|

Relations:
```
    "executorCorporation" => CorporationsEndpoint,
    "creatorCorporation"  => CorporationsEndpoint,
    "corporations"        => CorporationsEndpoint,
    "creatorCharacter"    => CharactersEndpoint,
```