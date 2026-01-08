# O que são pacotes e quadros

- Pacotes e quadros são pequenos pedaços de dados que, ao se formarem juntos, formam uma informação ou mensagem maior.
- Um pacote é um pedaço de dados da Camada 3 (Camada de Rede) do modelo OSI, contendo informações como um cabeçalho IP e carga útil.
- Um quadro é usado na Camada 2 (Data Link) do modelo OSI, que encapsula o pacote e adiciona informações adicionais, como endereços MAC.
- Os pacotes são uma maneira eficiente de comunicar dados entre dispositivos em rede.
- Os pacotes têm estruturas diferentes que dependem do tipo de pacote que está sendo enviado.

**cabeçalho pacote:**

- Time to Live (TTL) (define um temporizador de expiração para o pacote não obstruir a rede caso não consiga alcançar o destino).
- Checksum (fornece verificação de integridade; se algum dado for alterado, o valor será diferente do esperado).
- Endereço de origem (IP do dispositivo que envia o pacote).
- Endereço de destino (IP do dispositivo para o qual o pacote está sendo enviado).

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

**Cabeçalho:**

- Fonte Porto (Este valor é a porta aberta pelo remetente para enviar o pacote TCP de. Este valor é escolhido aleatoriamente, das portas de 0-65535 que ainda não estão em uso no momento).
- Porto Destino (Este valor é o número de porta que um aplicativo ou serviço está executando no host remoto (aquele que recebe dados); por exemplo, um servidor da Web executando na porta 80. Ao contrário da porta de origem, este valor não é escolhido aleatoriamente).
- Fonte IP (Este é o endereço IP do dispositivo que está enviando o pacote).
- IP de destino (Este é o endereço IP do dispositivo para o qual o pacote é destinado).
- Número da Sequência (Quando ocorre uma conexão, o primeiro pedaço de dados transmitido recebe um número aleatório. Vamos explicar isso mais aprofundadamente mais adiante).
- Número de reconhecimento (Depois que um pedaço de dados recebeu um número de sequência, o número para o próximo pedaço de dados terá o número de sequência + 1. Também explicaremos isso mais aprofundadamente adiante).
- Soma de verificação (Esse valor é o que dá integridade ao TCP. Um cálculo matemático é feito onde a saída é lembrada. Quando o dispositivo receptor realiza o cálculo matemático, os dados devem ser corrompidos se a saída for diferente do que foi enviado).
- Dados (Este cabeçalho é onde os dados, ou seja, bytes de um arquivo que está sendo transmitido, são armazenados).
- Bandeira (Este cabeçalho determina como o pacote deve ser tratado por qualquer dispositivo durante o processo de aperto de mão. Bandeiras específicas determinarão comportamentos específicos).

**aperto de mão de três vias se comunica usando algumas mensagens especiais:**

- SYN	
- SYN/ACK	
-	ACK	
-	DATA	
-	FIN	
-	RST

# UDP/IP: 

- O UDP é um protocolo que não requer uma conexão constante entre os dispositivos para enviar dados (não usa o aperto de mão).
- É usado quando pode haver perda de dados, como streaming e chamadas de voz.

**Cabeçalho:**

- Hora de viver (TTL) (Este campo define um temporizador de expiração para o pacote, para que ele não obstrua sua rede se ele nunca conseguir alcançar um host ou escapar!).
- Endereço de origem	(O endereço IP do dispositivo de onde o pacote está sendo enviado, para que os dados saibam para onde retornar).
- Endereço de destino	(O endereço IP do dispositivo para o qual o pacote está sendo enviado para que os dados saibam para onde viajar a seguir).
- Fonte Porto	(Este valor é a porta que é aberta pelo remetente para enviar o pacote UDP de. Este valor é escolhido aleatoriament, das portas de 0-65535 que ainda não estão em uso no momento).
- Porto Destino	(Este valor é o número da porta que um aplicativo ou serviço está executando no host remoto (aquele que recebe os dados); por exemplo, um servidor da Web executando na porta 80. Ao contrário da porta de origem, este valor não é escolhido aleatoriamente).
- Dados	(Este cabeçalho é onde os dados, ou seja, bytes de um arquivo que está sendo transmitido, são armazenados).

# Tarefas:

**1:**

**Qual é o nome de um pedaço de dados quando ele tem informações de endereçamento de IP?**

**Resposta:** Packet

**Qual é o nome para um pedaço de dados quando ele não possui informações de endereçamento de IP?**

**Resposta:** Frame

**2:**

**Qual é o cabeçalho em um pacote TCP que garante a integridade dos dados?**

**Resposta:** checksum

**Forneça a ordem de um aperto de mão normal de três vias (com cada passo separado por uma vírgula):**

c SYN,SYN/ACK,ACK 

**3 Prático - Handshake:**

<img width="906" height="856" alt="{859A1B06-2523-40DB-86B2-488FFBC18BA4}" src="https://github.com/user-attachments/assets/233618b0-689b-4814-8043-4619ee544503" />
<img width="615" height="301" alt="{24AC3B49-8DB9-4937-B8B2-553F3A0704A8}" src="https://github.com/user-attachments/assets/796d978f-029a-4e08-8fe7-dc992ffb6993" />
<img width="921" height="874" alt="{4D035608-36D4-408E-B125-87B109678311}" src="https://github.com/user-attachments/assets/9fb74b81-6d69-4609-abfe-505340667575" />

ACK antes Da Data.

<img width="909" height="855" alt="{99D42067-D6BC-4143-874C-47FF6B327FFE}" src="https://github.com/user-attachments/assets/2601448e-130d-4728-b56e-1ddcbde70830" />
<img width="593" height="230" alt="{68DB03EA-C6CB-4260-849B-C716D191E7DB}" src="https://github.com/user-attachments/assets/a325c191-7627-42a3-a11e-b335644dd611" />
<img width="653" height="274" alt="{4F6C272A-1DAF-4A6E-A416-7CD3890FBF4B}" src="https://github.com/user-attachments/assets/17ec975d-f52e-4bbb-a049-4989c154946b" />

ACK para confirmar o FIN.

**Resposta:** THM{TCP_CHATTER}

**4:**

**O que significa o termo "UDP"?**

**Resposta:** User Datagram ProtocolUser Datagram Protocol

**Que tipo de conexão é "UDP"?**

**Resposta:** stateless

**Qual protocolo você usaria para transferir um arquivo?**

**Resposta:** TCP

**Qual protocolo você usaria para ter uma chamada de vídeo?**

**Resposta:** UDP   

**5 Portos 101 (Prático):**

**Qual é a bandeira recebida do desafio?**

<img width="912" height="436" alt="{5A0515FC-30FD-4F8D-BBB9-456B65AA2748}" src="https://github.com/user-attachments/assets/ceb8594f-0797-4b09-8137-6f1ae55a7976" />

**Resposta:** THM{YOU_CONNECTED_TO_A_PORT}

# Aprendizado

- Pacote de quadros.
- Camdas TCP/IP.
- Cabeçalho TCP/IP e UDP/IP.
- Aperto de mão de três vias.

# Observação:

Eu já havia mencionado o tema na atividade 3—Modelo OSI sobre TCP e UDP, porém aqui eu me aprofundei e pude entender melhor como funciona esses modos de conexão.

O aperto de mão de três vias me deu uma perspectiva melhor de como uma conexão TCP é estabelecida.
A atividade 5 deste módulo me deu um teste prático que me mostrou o comando para estabelecer uma conexão por IP.




