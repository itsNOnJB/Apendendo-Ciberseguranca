# O que são pacotes e quadros

- Pacotes e quadros são pequenos pedaços de dados que, ao se formarem juntos, fazem uma informação ou mensagem maior.
- Um pacote é um pedaço de dados da camada 3 (camada de rede) do modelo OSI, contendo informações como um cabeçalho IP e carga útil.
- Um quadro é usado na Camada 2 (Data Link) do modelo OSI, que, encapsula o pacote e adiciona informações adicionais, como endereços MAC.
- Os pacotes são uma maneira eficiente de comunicar dados em dispositivos em rede.
- Os pacotes têm estruturas diferentes que dependem do tipo de pacote que está sendo enviado. 

**cabeçalho pacote:**

- Tempo para viver (Este campo define um temporizador de expiração para o pacote não obstruir sua rede se ele nunca conseguir alcançar um host ou escapar!)
- Soma de verificação (Este campo fornece verificação de integridade para protocolos como TCP /IP. Se algum dado for alterado, esse valor será diferente do esperado e, portanto, corrompido.)
- Endereço de origem (O endereço IP do dispositivo de onde o pacote está sendo enviado para que os dados saibam para onde retornar.)
- Endereço de destino (O endereço IP do dispositivo para o qual o pacote está sendo enviado para que os dados saibam para onde viajar a seguir.) 

# TCP/IP (O aperto de mão triplo)

**O protocolo TCP /IP consiste em quatro camadas e é indiscutivelmente apenas uma versão resumida do modelo OSI. Estas camadas são:** 

- Aplicação
- Transporte
- Internet
- Interface de rede

**TCP:**

- a informação é adicionada a cada camada do modelo TCP à medida que o pedaço de dados (ou pacote) o atravessa.
- Uma característica definidora do TCP é que ele é baseado em conexão, o que significa que deve estabelecer uma conexão entre um cliente e um dispositivo agindo como um servidor antes que os dados sejam enviados.
- TCP garante que quaisquer dados enviados serão recebidos na outra extremidade. (Este processo é nomeado o aperto de mão de três vias)

## Vantagens do TCP
