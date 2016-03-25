## Dogma

`dogma/`

| Route         | Status        |
| ------------- |:-------------:|
| GET           |`Route not found`|
| POST           |`WIP`|
| PUT           |`WIP`|
| SHOW          |`??`|

Relations:
```
    "attributes" => AttributesEndpoint,
    "effects"    => EffectsEndpoint,
```

## Dogma/Attributes

`dogma/attributes`

| Route         | Status        |
| ------------- |:-------------:|
| GET           |`Works`|
| POST           |`WIP`|
| PUT           |`WIP`|
| SHOW          |`Works`|

Relations:
```
    No relations
```

## Dogma/Effects

`dogma/effects`

| Route         | Status        |
| ------------- |:-------------:|
| GET           |`Works`|
| POST           |`WIP`|
| PUT           |`WIP`|
| SHOW          |`Works`|

Relations:
```
    "dischargeAttributeID" => Dogma/AttributesEndpoint,
    "durationAttributeID"  => Dogma/AttributesEndpoint,
```