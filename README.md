# Ejemplo de uso de Django REST Swagger

Para generar el esquema OpenAPI (formato yaml), se debería ejecutar:

```bash
cd example_app
python3 -m venv env
source env/bin/activate
pip install -r requirements.txt
pip install pyyaml
pip install pygments
python manage.py generateschema > openapi-schema.yml
```
