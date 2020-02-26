# data-store
Key value pair based data store

### Files
#### Source file
  - src/data_source.py

#### Test file
  - tests/test_data_store.py
  
#### UT Dependencies
  - pytest
  
#### Installing Dependencies
```sh
$ pip install -r requirements.txt
```
  
### Usage
#### Importing
```py
from src.data_store import DataStore
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
