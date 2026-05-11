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

3. To publish
