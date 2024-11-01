

# Socket Connection Guide


## Connect to the base url

```bash
http://194.163.173.171:3000/api/v1
```

## And listen to the `message` event

## Then send an emit to the socket to `join` with this message
// you can either join the room using join event or by sending a post request to the `/rooms/join` endpoint

```json
{
  "room": "", // room code
  "username": "" // username
}
```


## If you want to leave a room send an emit to the socket to `leave` with this message
// you can either leave the room using leave event or by sending a post request to the `/rooms/leave` endpoint

```json
{
  "room": "" // room code
}
```

## Done!
