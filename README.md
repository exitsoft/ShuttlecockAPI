![Shuttlecock Logo](./images/shuttlecock.png)

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

### Semester

For timetable during semester

###### Week

`Monday` to `Friday` on semester

```
$ curl https://nayunhwan.github.io/ShuttlecockAPI/semester/week.json
```

###### Saturday

`Saturday` or `holiday` on the semster

```
$ curl https://nayunhwan.github.io/ShuttlecockAPI/semester/sat.json
```

###### Sunday

`Sunday` on the semester

```
$ curl https://nayunhwan.github.io/ShuttlecockAPI/semester/sun.json
```

### Vacation

For timetable during vacation

###### Week

`Monday` to `Friday` on vacation

```
$ curl https://nayunhwan.github.io/ShuttlecockAPI/vacation/week.json
```

###### Saturday

`Saturday` or `holiday` on the vacation

```
$ curl https://nayunhwan.github.io/ShuttlecockAPI/vacation/sat.json
```

###### Sunday

`Sunday` on the vacation

```
$ curl https://nayunhwan.github.io/ShuttlecockAPI/vacation/sun.json
```
