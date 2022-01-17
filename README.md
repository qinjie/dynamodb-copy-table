# dynamodb-copy-table-python3
A simple python 3 script to copy dynamodb table

---

### Requirements

- Python 3.x
- boto (`pip install boto`)

### Usage

- A simple usage example:

```shell
set AWS_DEFAULT_PROFILE=xxx
python dynamodb-copy-table.py src_table dst_table
```

- To specify a region, e.g. `ap-southeast-1`.

```shell
python dynamodb-copy-table.py src_table dst_table ap-southeast-1
```

- To specify a profile, e.g. `profile-xxx`.

```shell
python dynamodb-copy-table.py src_table dst_table ap-southeast-1 profile-xxx
```
