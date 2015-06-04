interragir avec un script existant
===

execfile
---
```
execfile('mon_script.py')
```

import et reload
---
```
import test
# puis pour recharger si le code a change
reload(test)
```
il est a noter que le code du main ne s'executera pas.
Par contre, le code script hors main s'executera

pdb
---
a tester
