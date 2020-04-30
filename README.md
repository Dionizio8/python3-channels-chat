# @python3-channels-chat

## Introdução
Canais alteram o Django para trabalhar com código assíncrono por baixo dos panos e através do núcleo síncrono do Django, permitindo que os projetos do Django lidem não apenas com HTTP, mas também com protocolos que exigem conexões de longa execução - WebSockets, MQTT, chatbots, rádio amador e muito mais.

## Instalação
Em primeiro lugar entre no diretório do projeto e com o comando abaixo realize a criação do ambiente virtual:
```
python3 -m venv venv
```

Realize a instalação do da ultima versão do django:
```
pip install django
```

Realize a instação do channels:
```
python -m pip install -U channels
```

### Observação
O projeto foi realizado com base na documentação : [https://channels.readthedocs.io/en/latest/tutorial/part_2.html#] .