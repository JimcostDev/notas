## Instalación de FastAPI y Dependencias:
### Documentación:

[fastapi](https://fastapi.tiangolo.com/#installation)

---
**Instalar FastAPI:**
```bash
   pip install fastapi
   pip install uvicorn
   pip install pydantic
```
```python
from typing import Union
from fastapi import FastAPI

# Inicializar la instancia de FastAPI
app = FastAPI()

# Definir un endpoint básico
@app.get("/")
async def read_root():
    return {"message": "API de estandarización de menús"}

# Correr la API usando Uvicorn
if __name__ == "__main__":
    @app.get("/items/{item_id}")
    def read_item(item_id: int, q: Union[str, None] = None):
        return {"item_id": item_id, "q": q}
 ```
### Run it
```bash
   uvicorn main:app --reload
```
