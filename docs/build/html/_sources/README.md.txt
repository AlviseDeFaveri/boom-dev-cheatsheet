To build the docs:

1. First time

```bash
python3 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
```

2. To preview

```
make html
```

Then navigate to `file://<this folder>_build/html/index.html` from your browser.

Alternatively

```
make livehtml
navigate to 127.0.0.1:8000
```

3. To publish

Commit the `docs/` folder.
