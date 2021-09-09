# Dagster Research

Presentation: https://docs.google.com/presentation/d/18JdcftHOIA8wDgWAZKlerrdptOnENCQEZP1GTpX7ieQ/

## Run the demos

How to run this:

```bash
# Install stuff
python3 -m venv env
source env/bin/activate
pip install dagster dagit requests

# Run an example
dagit -f 3_complex_pipeline.py
```

Then go to the UI @ http://127.0.0.1:3000/workspace/__repository__complex_pipeline@3_complex_pipeline.py/pipelines/complex_pipeline:default/playground. Visit the pipeline -> Playground -> Launch
