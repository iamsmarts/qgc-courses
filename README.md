## quasargolf.club - courses

--
JSON data with course details for QGC challenges.

Compiling data to eventually build app for Quazar Golf Club challanges.
Current data collection is being done manually, unless a PUBLIC database or API is found.

Course data is collected as club challenges are planned.

Data Schema Example (WIP)

```
courses:[
  {
    name: String,
    course_id: Number,
    address: String,
    url: String,
    number_of_holes: Number,
    par: Number,
    course_type: String,
    driving_range: Boolean,
    putting_green: Boolean,
    chipping_green: Boolean,
    practice_bunker: Boolean,
    driving_cart: Boolean,
    push_cart: Boolean,
    weekday_price: Number,
    weekend_price: Number,
    twilight_price: Number,
    holes: Array[
        {
          course_id
          number: number,
          handicap: Number,
          par: Number
          tees: array[
              {
                  tee: String,
                  yards: Number,
              }
          ]
        }
    ]
  }
]
```
