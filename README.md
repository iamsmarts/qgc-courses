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
        name: 'String',
        id: Number,
        location: 'String'
        holesCount: Number,
        frontPar: Number,
        totalPar: Number,
        holes: Array[
            {
                number: number,
                tees: array[
                    {
                        tee: 'String',
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