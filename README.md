# Arquivo-PUB-SUB

# Projeto de Teste MQTT

# Requisitos

  Python 3.x

  Biblioteca paho-mqtt

  Broker MQTT (ex.: Mosquitto ou test.mosquitto.org)

# Instalação

# Clone o repositório:

  git clone https://github.com/seu-usuario/mqtt-projeto.git
cd mqtt-projeto

# Instale as dependências:

  pip install paho-mqtt

#  Como Testar

   Inicie o broker MQTT (se local, use mosquitto -v).

   Execute o publicador:

   python publisher.py

# Execute o assinante:

  python subscriber.py

# Conceitos Básicos do MQTT

  Broker: Servidor central que gerencia mensagens.

  Publicador: Envia mensagens para um tópico.

  Assinante: Escuta mensagens de um tópico.

  Tópicos: Canais de comunicação.
