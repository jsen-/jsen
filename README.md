# JSEN

JSON with comments, multi-line strings, optional quotes around object keys and allowed trailing commas.

### Example
```json5
{
    name: "Back to the Future",
    1985: "released",
    plot: "\"Back to the Future\" follows the adventures of Marty McFly,
a teenager who accidentally travels back in time to 1955 in a modified
DeLorean time machine invented by his friend, Dr. Emmett \"Doc\" Brown.
To ensure his own existence, Marty must navigate the past, reconcile his
parents' romance, and find a way back to his own time.",
    good: true,
    /* top cast: */
    starring: {
        "Michael J. Fox": "Marty McFly",
        "Christopher Lloyd": "Emmett \"Doc\" Brown",
        "Lea Thompson": "Lorraine Baines McFly",
        "Crispin Glover": "George McFly",
        "Thomas F. Wilson": "Biff Tannen",
    },
    "Directed by": "Robert Zemeckis",
    "Written by": [ "Robert Zemeckis", "Bob Gale" ],
    "Eric Stoltz": null,
    "Earnings ($ million)": 381.1,
    "": false, // empty string as key
}
```
