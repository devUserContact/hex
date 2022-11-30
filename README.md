# hex 
## A bash script for basic hexadecimal conversions 

The intended use case for this script is to improve workflows where hexadecimal, 
decimal, and normalized values (0-1) are employed. 

#### Options: 
```
-d2h, --dec-to-hex <0-255>
-n2h, --norm-to-hex <0-100>
-h2d, --hex-to-dec <00-ff>
-h2n, --hex-to-norm  <00-ff>"
```
#### Examples: 
```
$ sh hex -h2d ff ff ff 

255 255 255
```
```
$ sh hex -d2h 255 255 255 

#ffffff
```
