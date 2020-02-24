# data-store
Key value pair based data store

### Usage
#### Importing
```py
from data_store import DataStore, Lock
```
or
```py
from data_store import *
```

#### Initializing
```py
ds = DataStore('path_to_file.json')
```
or (this selects the default file in ./data_store/data_store.json
```
ds = DataStore()
```

#### Insert
```py
ds.insert('key','value')
```

#### Read
```py
ds.read('key')
```

#### Delete
```py
ds.delete('key')
```

#### Save (expilicit)
```py
ds.save()
```
