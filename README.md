ntc.js
======

A "fork" of ntc.js, originally by Chirag Mehta

Sample Usage
============
```js
<script type="text/javascript" src="js/ntc.js"></script>

<script type="text/javascript">

  var n_match  = ntc.name("#6195ED");
  n_rgb        = n_match[0]; // RGB value of closest match
  n_name       = n_match[1]; // Text string: Color name
  n_exactmatch = n_match[2]; // True if exact color match

  alert(n_match);

</script>
```
