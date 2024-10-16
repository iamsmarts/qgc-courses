## quasargolf.club - courses

--
JSON data with course details for QGC challenges.

Compiling data to eventually build app for Quazar Golf Club challanges.
Current data collection is being done manually, unless a public database or collection is found.

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
    driving_range: Boolean,
    putting_green: Boolean,
    chipping_green: Boolean,
    practice_bunker: Boolean,
    driving_cart: Boolean,
    push_cart: Boolean,
    holes: Array[
        {
          course_id
          number: number,
          tees: array[
              {
                  tee: String,
                  yards: Number,
                  handicap: Number,
                  par: Number
              }
          ]
        }
    ]
  }
]
```
