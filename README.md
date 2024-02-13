---
component-id: reeco-python-library
name: "REECO Python Library"
description: "The Python library of the REECO framework."
project: reeco-framework
type: SoftwareLibrary
doi: 10.5281/zenodo.10655153
credits:
- Enrico Daga <http://github.com/enridaga>
resource: https://pypi.org/project/reeco/

---
# REECO Python Library

Python library for the REECO framework.


## Schema

TBD

### Developers
Editing happens in this [Spreadsheet](https://docs.google.com/spreadsheets/d/1PZ11esT6COK7Y0mMZEHifY9hQeREbNSlRbC6dkYtjNg/edit?usp=sharing).

The reference documentation is in folder `schema/`.

To regenerate the `yaml` files in the schema directory:
```bash
python3 generate-schema.py && git add schema/ && git commit -m "Update" && git push
```

## Validator

TBD
