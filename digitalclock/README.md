# Javascript digital clock
Easy to create digital clock to your webpage

## How to use?

1. Download digitalclock.min.js file in this repository and link to your html head 

<script src="../digitalclock.js"></script>
or simply you can use like this
<script src="https://kykurniawan.github.io/library/digitalclock/digitalclock.min.js"></script>

2. Create digital clock element in your page like this

<span id="digital-clock" data-clockFormat="hms" data-clockSeparator=":"></span>

-- data-clockFormat attribute
hms -> will create clock with format like 00:00:00
hm -> will create clock with format like 00:00
h -> will create clock with format like 00

-- data-clockSeparator attribute
you can change separator for your clock
example:
data-clockSeparator=":" -> will create clock with separator like 00:00:00
data-clockSeparator="-" -> will create clock with separator like 00-00-00
data-clockSeparator="/" -> will create clock with separator like 00/00/00
