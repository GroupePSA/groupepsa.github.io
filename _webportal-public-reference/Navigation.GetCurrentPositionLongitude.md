---
title: Navigation.GetCurrentPositionLongitude()

supported:
  - 2
  - 3
  - 4
type: api
privacy: Public
---

### `Navigation.GetCurrentPositionLongitude()`

| **Description** | Gets the current position's longitude in WGS84 Signed Decimal Degrees.
| **Response** | *Number*  Current position's longitude as WGS84 Signed Decimal Degrees.
| **Parameter**   | *Void*

#### EXAMPLE

```javascript
var CurrentLongitude = Navigation.GetCurrentPositionLongitude();
// CurrentLongitude = 2.333333
```

#### REMARK

>**Note :** The returned longitude's length < 11 characters.

*Appeared in Software version 40.03.42.30*