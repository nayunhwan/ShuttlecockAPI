# Shuttlecock API
API to get timetable of Shuttlebus in Hanyang University ERICA

## Usage
If you want to get timetable for Shuttlebus of Hanyang University ERICA, just send `GET` HTTP request to `https://nayunhwan.github.io/ShuttlecockAPI/semester/:params`

## API Documents
This phase describes about word in this API

### Bus stop
* `shuttleA`: The bus stop at Shuttlecock to go to Hanyang University at Ansan Station
* `shuttleB`: The bus stop at Shuttlecock to go to Express bus terminal at Ansan
* `subway`: The bus stop at Hanyang University at Ansan Station
* `terminal`: The bus stop at Express bus terminal at Ansan
* `dorm`: The bus stop at Dormitory in Hanyang University

### Bus type
* `toSubway`: The bus to go to Hanyang Univeristy at Ansan Station
* `toTerminal`: The bus to go to Express bus terminal at Ansan
* `cycle`: The bus for cycle route

### semester
For timetable during semester

#### Week
`Monday` to `Friday` on semester

```
$ curl https://nayunhwan.github.io/ShuttlecockAPI/semester/week.json
```
