# Usando FastAPI

##  Instalar extensões
1.	Thunder Client
1.	Python
1.  Material Icons
   
## Rodar no cmd
1.	```python -m venv ambiente``` para criar o ambiente
1.	```ambiente\Scripts\activate``` esse comaando serve para ativar os scripts no ambiente criado
1.  Rodar ```pip install fastapi uvicorn```
1.  Com o ```pip freeze``` conseguimos ver todas as bibliotecas baixadas no pip 
1.  ```pip freeze > requirements.txt``` para criarmos um arquivo com todas as bibliotecas instaladas com o pip
1.  Endpoint para ser usado é o ```uvicorn main:app --host 127.0.0.1 --port:8000``` 
