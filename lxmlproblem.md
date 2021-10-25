#Problem : psycopg2.ProgrammingError: relation "ir_model" does not exist
LINE 1: SELECT * FROM ir_model WHERE state='manual'/Extra content at the end of the documen

```sh
rm -rf venv
virtualenv -p pythonx venv
source venv/bin/activate
pip install -r requirements.txt
pip uninstall lxml
find .cache -name 'lxml*'
find .cache -name 'lxml*' -delete
pip install lxml
```
