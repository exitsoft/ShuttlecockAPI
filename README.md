![Shuttlecock Logo](./images/shuttlecock.png)

# Shuttlecock API

API to get timetable of Shuttlebus in Hanyang University ERICA

## Demo
[http://shuttlecock.kr](http://shuttlecock.kr)

## Usage

If you want to get timetable for Shuttlebus in Hanyang University ERICA, just send `GET` HTTP request to `https://nayunhwan.github.io/ShuttlecockAPI/:term/:params`

## API Documents

This phase describes about word in this API

### Bus stop

* `shuttleA`: The bus stop at Shuttlecock to go to Hanyang University at Ansan Station
* `shuttleB`: The bus stop at Shuttlecock to go to Express bus terminal at Ansan
* `subway`: The bus stop at Hanyang University at Ansan Station
* `terminal`: The bus stop at Express bus terminal at Ansan
* `dorm`: The bus stop at Dormitory in Hanyang University ERICA

### Bus type

* `toSubway`: The bus to go to Hanyang Univeristy at Ansan Station
* `toTerminal`: The bus to go to Express bus terminal at Ansan
* `cycle`: The bus for cycle route

### Semester

For timetable during semester

###### Week

`Monday` to `Friday` on semester

```
$ curl https://exitsoft.github.io/ShuttlecockAPI/semester/week.json
```

###### Holiday

`Saturday` or `holiday` on semster

```
$ curl https://exitsoft.github.io/ShuttlecockAPI/semester/holiday.json
```

### Vacation

For timetable during vacation

###### Week

`Monday` to `Friday` on vacation

```
$ curl https://exitsoft.github.io/ShuttlecockAPI/vacation/week.json
```

###### Saturday

`Saturday` or `holiday` on vacation

```
$ curl https://exitsoft.github.io/ShuttlecockAPI/vacation/sat.json
```

###### Sunday

`Sunday` on vacation

```
$ curl https://exitsoft.github.io/ShuttlecockAPI/vacation/sun.json
```
