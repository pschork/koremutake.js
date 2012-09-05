koremutake.js
=============

Convert to and from Koremutake Memorable Random Strings in Javascript

Koremutake is a 128bit MeRS encoding algorithm that can convert any large, 
unsigned number into a memorable sequence of phonetically unique syllables.

For details see http://shorl.com/koremutake.php

```
<script>
    koremutake.encode(10610353957)   // 'koremutake'
    koremutake.decode('koremutake')  // 10610353957
</script>
```
