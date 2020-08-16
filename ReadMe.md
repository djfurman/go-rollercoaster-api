# Go roller coaster

Silly little simple example Go Rest API

My implementation of Zero dependency Rest API in Go [by kubucation](https://www.youtube.com/watch?v=2v11Ym6Ct9Q)

## Plan

- Use no external libraries
- Build a rest API
- Check for `application/json` Accept header, throw `415 Unsupported Media Type` if not present
- Implement JSON response model
- In memory persistence

### Data model

```json
{
    "id": "someId",
    "name": "name of the roller coaster",
    "inPark": "name of the amusement park",
    "manufacturer": "name of the manufacturer",
    "height": 27
}
```

## Enhancement

- Add dynamoDB persistence

## Personal note

I really don't like roller coasters or amusement parks, but this example is really well thought out and demonstrates features I can actually use as colleages and friends continue to urge me to become a Gopher.
