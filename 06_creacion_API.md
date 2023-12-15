### Instalación de FastAPI y Dependencias:
**Instalar FastAPI:**
```bash
   pip install fastapi
   pip install uvicorn
   pip install pydantic
```
```python
  from fastapi import FastAPI
  
  # Inicializar la instancia de FastAPI
  app = FastAPI()
  
  # Definir un endpoint básico
  @app.get("/")
  async def read_root():
      return {"message": "API de estandarización de menús"}
  
  # Correr la API usando Uvicorn
  if __name__ == "__main__":
      import uvicorn
      uvicorn.run(app, host="0.0.0.0", port=8000)
 ```
