> Pyspark Sample project

Docker environment created to students learn how to build and create your first interaction with pyspark and kafka

### Requirements and configure:
```sh
* You will need: 
*      docker and docker-compose (no maters if you running on windows, linux or mac)
*      git installed
* git clone https://github.com/marcosvasconcelos/sample-pyspark.git
* cd ~/sample-pyspark
* docker-compose start
* 
```

Todas as imagens necessárias serão carregadas e uma imagem do jupyter-notebook será compilada para a integração com o elasticsearch

# Mapeamento

| Container     | Porta | Usuario   | Senha     |
|---------------|-------|-----------|-----------|
| jupyter       | 8888  |  N/A      | teste     |
| kafkadrop     | 19000 |  N/A      | N/A       |
| kafka         | 29092 |  N/A      | N/A       |
