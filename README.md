# stack-redis

Redis deployment.

## Tooling

The ``pyclient`` can be used for a manual backup/restore.

Requirements: ``Python3``, an enabled ``virtualenv``, and the following Python modules: ``click``, ``redis``, ``python-dotenv``.

```bash
# Setup venv/deps
python3 -m venv venv
source venv/bin/activate
python3 -m pip install click redis python-dotenv

# Run tooling
deployment tools pyclient <pull|push>
```
