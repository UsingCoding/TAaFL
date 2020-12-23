### Tokens
#### ID:

 `^[a-z][a-zA-Z\d]*$`


#### KEYWORDS:

[
    if, fi
    for, rof,
    became - to declare var
    const - to declare const,
    int,
    double,
    string
]


#### NUMBERS:

[
    int = `\d*`
    double = `\d*\.\d*`
    int = `bx(1|0)*`
    double = `bx(1|0)*\.(1|0)+`
    int = `0x[\dA-Fa-f]+`
    double = `0x[\dA-Fa-f]+\.[\dA-Fa-f]+`
]


#### DIVIDERS:

[
    . , -> =
]


#### OPERATIONS:

[
    +,
    -,
    *,
    /
]


#### COMMENTS

[
    //
    /@ @/
]


#### SPACE STATE:

' ' - is divider
