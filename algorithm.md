A special case:

- name: a-z, 0-9, no A-Z
- version
- path: _ . -
- ext
- more than one package
- root

Serialization algorithm with convension will be extreme powerful.

```
~mod~zepto-wepp~1.1.3~a/b_c.d.min.js,~mod~underscore2~1.5.3~underscore2.min.js
```

```
~mod~zepto-wepp~1.1.3~a/b_c.d.min.js,~mod~underscore2~1.5.3~underscore2.min.js
```

```
// <ext>/<root>/<name>/<version>[/<path>],...
min.js/mod/zepto-wepp/1.1.3/a/b_c.d,mod/underscore2/1.5.3/
```

```
1.1.3 -> 10103
1.5.3 -> 10503

0123456789
abcdefghij

min/mod/zepto-wepp/babad/a/b_c.d,mod/underscore2/bafad
.js

2 -> //d 
_ -> //k
, -> '

min/mod/zepto-wepp/babad/a/b//kc.d'mod/underscore//d/bafad
.js
```

```
abcdefghijklmnopqrstuvwxyz-./'
abcdefghijklmnopqrstuvwxyz-./'ABCDEFGHIJKLMNOPQRSTUVWXYZ0123456789~!*()_
```

Then dot the number system conversion.

Limit compress rate: 0.5 * 30 / 72 = 0.21

```
ctx.io/_/zepto/1.1.3/a/b_c.d.min.js
ctx.io/_c/


