# Introdução de Topologias LAN

**Rede Local (LAN) Topologias**:

- Star Topology.
- Bus Topology.
- Ring topology.

**O que é um Switch?**

- Switches são dispositivos dedicados dentro de uma rede.
- são projetados para agregar vários outros dispositivos, como computadores, impressoras ou qualquer outro dispositivo compatível com rede usando ethernet.
- Switches são geralmente encontrados em redes maiores, como empresas, escolas ou redes de tamanho semelhante.
- Switches podem conectar um grande número de dispositivos por ter portas de 4, 8, 16, 24, 32 e 64 para dispositivos se conectarem.
- Os switches acompanham qual dispositivo está ligado a qual porta.
- Switches e Roteadores podem ser conectados uns aos outros.

**O que é um roteador?**

- um roteador conectar redes e passar dados entre elas.
- O roteamento envolve a criação de um caminho entre as redes para que esses dados possam ser entregue com sucesso.
- O roteamento é útil quando os dispositivos são conectados por muitos caminhos.

# Um Primer sobre Sub-rede: 

- Sub-rede é o termo dado para dividir uma rede em redes menores e em miniatura dentro de si.
- Os administradores de rede usam a sub-rede para categorizar e atribuir partes específicas de uma rede para refletir isso.
- A sub-rede é conseguida dividindo o número de hosts que podem caber dentro da rede, representado por um número chamado máscara de sub-rede.
- sub-rede que também é representada como um número de quatro bytes (32 bits), variando de 0 a 255 (0-255).

**As sub-redes usam endereços IP de três maneiras diferentes:**

- Identificar o endereço de rede.
- Identificar o endereço do host.
- Identificar o gateway padrão.

**A sub-rede oferece uma gama de benefícios, incluindo:**

- Eficiência
- Segurança
- Controle total

# ARP: 

- ARP é a tecnologia que é responsável por permitir que os dispositivos se identifiquem em uma rede.
- o ARP permite que um dispositivo associe seu endereço MAC a um endereço IP na rede.
- Os dispositivos podem usar o ARP para encontrar o endereço MAC (e, portanto, o identificador físico) de um dispositivo para comunicação.

**Como ARP funciona o ARP?**

- ARP armazena cache que indentifica outros dispositivos na rede.

**ARP envia dois tipos de mensagens:**

- Solicitação ARP.
- Resposta ARP.

# DHCP: 

- Quando um dispositivo se conecta a uma rede, se ele ainda não recebeu um endereço IP manualmente, ele envia uma solicitação (DHCP Discover) para ver se algum servidor DHCP está na rede.
- O servidor DHCP responde de volta com um endereço IP que o dispositivo poderia usar (DHCP Offer).
- ODHCP envia uma resposta confirmando que deseja o endereço IP oferecido (Solicitação DHCP) e, por último, o servidor DHCP envia uma resposta reconhecendo que isso foi concluído e o dispositivo pode começar a usar o endereço IP (DHCP ACK).

# tarefas: 

**1:**

**O que representa a LAN?**
**Resposta:** Local Area Network

**Qual é o verbo dado ao trabalho que os Roteadores executam?**
**Resposta:** Routing 

**Qual dispositivo é usado para conectar centralmente vários dispositivos na rede local e transmitir dados para o local correto?**
**Resposta:** Switch

**Qual topologia é econômica para configurar?** 
**Resposta:** Bus Topology

**Qual topologia é cara para configurar e manter?**
**Resposta:** Star Topology

**Complete o laboratório interativo anexado a esta tarefa. O que a bandeira é dada no final?**

Ring topology desvantagem:

<img width="925" height="873" alt="{9267CA04-5F08-4623-BC5E-0C61FC26F9CE}" src="https://github.com/user-attachments/assets/eb1ee8fa-dc79-45ab-aa70-5a368e5f28c0" />
<img width="923" height="863" alt="{7F57D062-5646-44CB-BAAD-1FB62C81C09C}" src="https://github.com/user-attachments/assets/902eaf68-efe7-45f9-a155-a3b6c14150ad" />

Bus topology desvantagem:

<img width="922" height="868" alt="{9DB8FC35-8D5B-473A-8492-400B8CF120E2}" src="https://github.com/user-attachments/assets/fc29d03c-67f7-4dd8-84b9-8face26690dd" />
<img width="905" height="872" alt="{0F0D3143-4FDC-4D43-8F50-AE78EAD381D1}" src="https://github.com/user-attachments/assets/83cec003-145b-4145-b886-4de00f8ad7a9" />

Star topology desvantagem:

<img width="925" height="744" alt="{A8E3414C-CF04-442A-AE2B-71745028CAFC}" src="https://github.com/user-attachments/assets/872f1efb-7015-4fcb-b32f-538aec3d50ce" />
<img width="922" height="730" alt="{9ECE35F1-BD55-4A0D-AD23-BE997614C189}" src="https://github.com/user-attachments/assets/4fd38c52-dc1b-42bb-bd72-4abe46851ac1" />
<img width="329" height="226" alt="{AC422A5C-A183-4DE3-A4B9-AE03B1AA76AF}" src="https://github.com/user-attachments/assets/af41e6c8-9e13-4081-ac57-06d20beafb81" />

**Resposta:** THM{TOPOLOGY_FLAWS} 

**2:**

**Qual é o termo técnico para dividir uma rede em pedaços menores?**
**Resposta:** Subnetting

**Quantos bits estão em uma máscara de sub-rede?**
**Resposta:** 32 

**Qual é o alcance de uma seção (octeto) de uma máscara de sub-rede?**
**Resposta:** 0-255

**Qual endereço é usado para identificar o início de uma rede?**
**Resposta:** Network Address

**Qual endereço é usado para identificar dispositivos dentro de uma rede?**
**Resposta:** Host Address

**Qual é o nome usado para identificar o dispositivo responsável pelo envio de dados para outra rede?**
**Resposta:** Default Gateway

**3:**

**O que significa ARP?**
**Resposta:** Address Resolution Protocol

**Qual categoria de Pacote ARP pergunta a um dispositivo se ele tem ou não um endereço IP específico?**
**Resposta:** Request

**Qual endereço é usado como identificador físico para um dispositivo em uma rede?**
**Resposta:** MAC Address

**Qual endereço é usado como um identificador lógico para um dispositivo em uma rede?**
**Resposta:** IP Address

**4:** 

**Que tipo de pacote DHCP é usado por um dispositivo para recuperar um endereço IP?**
**Resposta:** DHCP Discover

**Que tipo de pacote DHCP um dispositivo envia uma vez que lhe foi oferecido um endereço IP pelo servidor DHCP?**
**Resposta:** DHCP Request

**Por fim, qual é o último pacote DHCP que é enviado para um dispositivo de um servidor DHCP?**
**Resposta:**  DHCP ACK 

# Aprendizado

- Rede lan e suas topologias.
- Switch são bem caros de manter, mas tambem muito eficientes para grandes negocios.
- Roteador serve para roteaamento de dados, prioriza o trafego para melhor desempenho.
- Sub-redes são muito eficientes para controlar dispositicos garantir sua segurança e ter mais eficiencia.
- ARP e fundamental para o reconhecimento de redes.
- DHCP abre solicitações para o uso de um IP em uma rede. 

# Observação:

Muito interessante saber como funciona o trafego de uma rede como são os passos, suas fraquezas e beneficios
isso ira me agregar muito sobre redes e fundamental para meu desenvolvimento.

