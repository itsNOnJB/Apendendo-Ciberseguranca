#  O que é o modelo OSI?

- O modelo OSI é um modelo essencial usado em rede.
- Este modelo crítico fornece uma estrutura que dita como todos os dispositivos em rede enviarão, receberão e interpretarão dados.
- O modelo OSI padroniza a comunicação em rede, permitindo interoperabilidade entre dispositivos e fabricantes diferentes.
- Os dados enviados através de uma rede que segue a uniformidade do modelo OSI podem ser entendidos por outros dispositivos.
- O modelo OSI consiste em sete camadas.

# Camada 1 - fisica:

- essa camada faz referência aos componentes físicos do hardware usado na rede e é a camada mais baixa que você encontrará.
- Os dispositivos usam sinais elétricos, ópticos ou de rádio para transmitir dados em binário (0 e 1).

# Camada 2 - Link de dados:

- A camada de Link de dados se concentra na abordagem física da transmissão.
- Ele recebe um pacote da camada de rede (incluindo o endereço IP para o computador remoto) e adiciona no endereço físico MAC (Media Access Control) do endpoint de recebimento.
- camada de link de dados apresentar os dados em um formato adequado para transmissão.
- Responsável por switches e controle de acesso ao meio (CSMA/CD).

# Camada 3 - Rede (roteamento): 

- o roteamento simplesmente determina o caminho mais ideal no qual esses pedaços de dados devem ser enviados.
- Endereços lógicos (IP)

**fatores que decidem qual rota  é tomada são decididos pelo seguinte:**

- Qual caminho é o mais curto? Ou seja, tem a menor quantidade de dispositivos que o pacote precisa para viajar.
- Qual caminho é o mais confiável? Ou seja, já foram perdidos pacotes nesse caminho antes?
- Qual caminho tem a conexão física mais rápida? Ou seja, um caminho é usando uma conexão de cobre (mais lenta) ou uma fibra (consideravelmente mais rápida)?

# Camada 4 - Transporte: 

**Quando os dados são enviados entre dispositivos, ele segue um dos dois protocolos diferentes que são decididos com base em vários fatores:** 

- TCP
- UDP

**(TCP):**

- este protocolo é projetado com confiabilidade e garantia em mente.
- Este protocolo reserva uma conexão constante entre os dois dispositivos pela quantidade de tempo que leva para que os dados sejam enviados e recebidos.
- o TCP incorpora a verificação de erros em seu design.
- verificação de erros é como o TCP pode garantir que os dados enviados dos pequenos pedaços na camada de sessão (camada 5) foram recebidos e remontados na mesma ordem.
- O TCP é usado para situações como compartilhamento de arquivos, navegação na Internet ou envio de um e-mail.

 **Vantagens do TCP:**

- Garante a precisão dos dados.
- Capaz de sincronizar dois dispositivos para evitar que um ao outro seja inundado com dados.
- Realiza muito mais processos de confiabilidade. 

**Desvantagens do TCP:**

- Requer uma conexão confiável entre os dois dispositivos. Se um pequeno pedaço de dados não for recebido, então todo o pedaço de dados não pode ser usado.
- Uma conexão lenta pode gargalar outro dispositivo, pois a conexão será reservada no computador receptor o tempo todo.
- O TCP é significativamente mais lento que o UDP, porque mais trabalho tem que ser feito pelos dispositivos que usam este protocolo.

**UDP:**

- Este protocolo não é tão avançado como o seu irmão - o protocolo TCP.
- Ele não possui os muitos recursos oferecidos pelo TCP, como verificação de erros e confiabilidade.
- Qualquer dado que é enviado via UDP é enviado para o computador, quer chegue lá ou não. 
- Não há sincronização entre os dois dispositivos ou garantia; apenas espero o melhor e os dedos cruzados.

**Vantagens do UDP:** 

- UDP é muito mais rápido que TCP.
- O UDP deixa a camada de aplicativo (software do usuário) para decidir se há algum controle sobre a rapidez com que os pacotes são enviados.
- A UDP não reserva uma conexão contínua em um dispositivo como o TCP.

**Desvantagens da UDP:**

- A UDP não se importa se os dados são recebidos.
- É bastante flexível para desenvolvedores de software nesse sentido.
- Isso significa que as conexões instáveis resultam em uma experiência terrível para o usuário.

# Camada 5 - Sessão: 

- A camada de sessão (camada 5) começará a criar e manter a conexão com outro computador para o qual os dados estão destinados.
- Quando uma conexão é estabelecida, uma sessão é criada.
- Embora essa conexão esteja ativa, a sessão também está. 
- A camada de sessão também é responsável por fechar a conexão se ela não tiver sido usada em algum tempo ou se for perdida. 
- uma sessão pode conter "pontos de verificação", onde se os dados forem perdidos, apenas os mais novos dados devem ser enviados, economizando largura de banda. 

# Camada 6 - Apresentação: 

- A camada 6 do modelo OSI é a camada na qual a padronização começa a ocorrer.
- Como os desenvolvedores de software podem desenvolver qualquer software, como um cliente de e-mail de forma diferente, os dados ainda precisam ser tratados da mesma maneira – não importa como o software funcione.
- Esta camada atua como um tradutor para dados para a camada de aplicação (camada 7). 
- Criptografia
- Compressão
- Codificação

# Camada 7 - Aplicação:

- A camada de aplicativo é a camada em que protocolos e regras estão em vigor para determinar como o usuário deve interagir com os dados enviados ou recebidos.
- Aplicativos diários, como clientes de e-mail, navegadores ou software de navegação no servidor de arquivos, como o FileZilla, fornecem um interface (GUI). 


# Tarefas: 

**1:**

**O que significa o "OSI" no "OSI Model"?**

**Resposta:** Open Systems Interconnection

**Quantas camadas (em dígitos) tem o modelo OSI?**

**Resposta:** 7

**Qual é o termo-chave para quando as informações são adicionadas aos dados?**

**Resposta:** encapsulation

**2:**

**Qual é o nome desta camada?**

**Resposta:** Physical

**Qual é o nome do sistema de numeração que é ambos 0's e 1's?**

**Resposta:** Binary

**Qual é o nome dos cabos que são usados para conectar dispositivos?**

**Resposta:** Ethernet Cables

**3:**

**Qual é o nome desta camada?**

**Resposta:** Data Link

**Qual é o nome do hardware que todos os dispositivos em rede vêm com?**

**Resposta:** Network Interface Card 

**4:** 

**Qual é o nome desta camada?** 

**Resposta:** Network

**Os pacotes seguirão a rota mais ideal em uma rede? (Y/N)** 

**Resposta:** Y

**O que significa a sigla "OSPF"?** 

**Resposta:** Open Shortest Path First

**O que significa o acrônimo "RIP"?** 

**Resposta:** Routing Information Protocol

**Que tipo de endereços são tratados nesta camada?Qual é o nome desta camada?**

**Resposta:** IP Addresses

**5:** 

**Qual é o nome desta camada?**

**Resposta:** Transport

**O que significa TCP?**

**Resposta:** Transmission Control Protocol

**O que representa a UDP?**

**Resposta:** User Datagram Protocol

**Qual protocolo garante a precisão dos dados?**

**Resposta:** TCP

**Qual protocolo não se importa se os dados são recebidos ou não pelo outro dispositivo?**

**Resposta:** UDP

**Que protocolo um aplicativo, como um cliente de e-mail, usaria?**

**Resposta:** TCP

**Qual protocolo um aplicativo que baixa arquivos usaria?**

**Resposta:** TCP

**Qual protocolo um aplicativo que transmite o uso de vídeo?**

**Resposta:** UDP

**6:** 

**Qual é o nome desta camada?**

**Resposta:** Session

**Qual é o termo técnico para quando uma conexão é estabelecida com sucesso?**

**Resposta:** Session

**7:**

**Qual é o nome desta camada?**

**Resposta:** Presentation

**Qual é o principal objetivo que esta camada atua como?**

**Resposta:** Translator

**8:**

**Qual é o nome desta camada?**

**Resposta:** Application

**Qual é o termo técnico que é dado ao nome do software com o qual os usuários interagem?**

**Resposta:** Graphical User Interface

**9:**

**Fuja da masmorra para recuperar a bandeira. O que é a bandeira?**

<img width="505" height="763" alt="{9CF2A099-4FA3-42FE-B714-D61A4BC78264}" src="https://github.com/user-attachments/assets/8eb47cd8-43e7-4562-91da-8214b6d0f2f7" />
<img width="506" height="767" alt="{B6AE0F89-278A-48A6-90DE-CFC20A9585A2}" src="https://github.com/user-attachments/assets/9c352c70-a5c9-4d63-8555-d30ca2b43ace" />

**Resposta:** THM{OSI_DUNGEON_ESCAPED}

# Aprendizado: 

- O que e modelo OSI e suas camadas.
- Como cada camada funciona.
- Como e importante o modelo OSI para conexão e envio de dados

# Observação: 

Fundamentos de redee esta sendo escensial pra mim saber os fatores de rede e muito importante não so para meu desenvolvimento
mas para meu dia a dia onde sempre estou navegando acessando  sites depois dessa atividade vou navegar com outros olhos pela internet.

