## Characters

`characters/` `AUTH`

| Route         | Status        |Scope|
| ------------- |:-------------:|:-------------:|
| GET           |`Authentication scope needed`|
| POST           |`WIP`|
| PUT           |`WIP`|
| SHOW          |`Works`|

Relations:
```
    "standings"     => StandingsEndpoint,
    "bloodLine"     => BloodLinesEndpoint,
    "waypoints"     => Characters/WaypointsEndpoint,
    "private"       => Characters/PrivateEndpoint,
    "channels"      => Characters/ChannelsEndpoint,
    "blocked"       => Characters/BlockedEndpoint,
    "fittings"      => Characters/FittingsEndpoint,
    "contacts"      => Characters/ContactsEndpoint,
    "location"      => Characters/LocationEndpoint,
    "mail"          => Characters/MailEndpoint,
    "capsuleer"     => Characters/CapsuleerEndpoint,
    "vivox"         => Characters/VivoxEndpoint,
    "notifications" => Characters/NotificationsEndpoint,
    "corporation"   => CorporationsEndpoint,
    "race"          => RacesEndpoint,
    "accounts"      => AccountsEndpoint,
```

## Characters/Blocked

`characters/[ID]/blocked` `AUTH`

| Route         | Status        |Scope|
| ------------- |:-------------:|:-------------:|
| POST           |`WIP`|
| PUT           |`WIP`|
| SHOW          |`Authentication scope needed`|


Relations:
```
    No relations
```

## Characters/Capsuleer

`characters/[ID]/capsuleer` `AUTH`

| Route         | Status        |Scope|
| ------------- |:-------------:|:-------------:|
| POST           |`WIP`|
| PUT           |`WIP`|
| SHOW          |`Not Third Party Enabled`|

Relations:
```
    No relations
```

## Characters/Channels

`characters/[ID]/chat/channels/` `AUTH`

| Route         | Status        |Scope|
| ------------- |:-------------:|:-------------:|
| POST           |`WIP`|
| PUT           |`WIP`|
| SHOW          |`Works`|

Relations:
```
    No relations
```

## Characters/Contacts

`characters/[ID]/contacts/` 

| Route         | Status        |Scope|
| ------------- |:-------------:|:-------------:|
| POST           |`WIP`|`characterContactsWrite`|
| PUT           |`WIP`|`characterContactsWrite`|
| SHOW          |`Works`|`characterContactsRead`|

Relations:
```
    No relations
```

## Characters/Fittings

`characters/[ID]/fittings/` `AUTH`

| Route         | Status        |Scope|
| ------------- |:-------------:|:-------------:|
| POST           |`WIP`|`characterFittingsWrite`|
| PUT           |`WIP`|`characterFittingsWrite`|
| SHOW          |`Works`|`characterFittingsRead`|

Relations:
```
    No relations
```

## Characters/Location

`characters/[ID]/location/` `AUTH`

| Route         | Status        |Scope|
| ------------- |:-------------:|:-------------:|
| POST           |`WIP`|
| PUT           |`WIP`|
| SHOW          |`Works`|`characterLocationRead`|

Relations:
```
    No relations
```

## Characters/Mail

`characters/[ID]/mail/` `AUTH`

| Route         | Status        |Scope|
| ------------- |:-------------:|:-------------:|
| POST           |`WIP`|
| PUT           |`WIP`|
| SHOW          |`Authentication scope needed`|

Relations:
```
    No relations
```

## Characters/Notifications

`characters/[ID]/notifications` `AUTH`

| Route         | Status        |Scope|
| ------------- |:-------------:|:-------------:|
| POST           |`WIP`|
| PUT           |`WIP`|
| SHOW          |`Works`|

Relations:
```
    No relations
```

## Characters/Private

`characters/[ID]/private` `AUTH`

| Route         | Status        |Scope|
| ------------- |:-------------:|:-------------:|
| POST           |`WIP`|
| PUT           |`WIP`|
| SHOW          |`Not Third Party Enabled`|

Relations:
```
    No relations
```

## Characters/Vivox

`characters/[ID]/vivox` `AUTH`

| Route         | Status        |Scope|
| ------------- |:-------------:|:-------------:|
| POST           |`WIP`|
| PUT           |`WIP`|
| SHOW          |`Not Third Party Enabled`|

Relations:
```
    No relations
```

## Characters/Navigation/Waypoints

`characters/[ID]/navigation/waypoints/` `AUTH`

| Route         | Status        |Scope|
| ------------- |:-------------:|:-------------:|
| POST           |`WIP`|`characterNavigationWrite`|
| PUT           |`WIP`|`characterNavigationWrite`|
| SHOW          |`Works`|
Relations:
```
    No relations
```