# All api endpoints for philips hue
## Lights
| METHOD | URL | Desc |
| ------ | --- | ---- |
| GET    | /api/\<username>/lights | List all lights |
| GET    | /api/\<username>/lights/new | List all new lights |
| GET    | /api/\<username>/lights/\<id> | Get info about light with id \<id> |
| POST   | /api/\<username>/lights | Search for new lights |
| PUT    | /api/\<username>/lights/\<id> | Change name of light with id \<id> |
| PUT    | /api/\<username>/lights/\<id>/state | Change the state of light with id \<id> |
| DELETE | /api/\<username>/lights/\<id> | Delete light with id \<id> |

## Groups
| METHOD | URL | Desc |
| ------ | --- | ---- |
| GET    | /api/\<username>/groups | List all groups |
| POST   | /api/\<username>/groups | Create a group |
| GET    | /api/\<username>/groups/\<id> | Get info about group with id \<id> |
| PUT    | /api/\<username>/groups/\<id> | Modify group with id \<id> |
| PUT    | /api/\<username>/groups/\<id>/action | Modify all lights within a group with id \<id> |
| DELETE | /api/\<username>/groups/\<id> | Delete group with id \<id>

## Configuration
| METHOD | URL | Desc |
| ------ | --- | ---- |
| POST   | /api | Create user |
