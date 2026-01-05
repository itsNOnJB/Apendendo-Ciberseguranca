# Introdução à Segurança Defensiva:

**tarefas principais**:

- Impedir que ocorram intrusões.
- Detectando intrusões quando elas ocorrem e respondendo corretamente.

**Algumas das tarefas relacionadas à segurança defensiva incluem:**

- Consciência de segurança cibernética do usuário: treinar usuários sobre segurança cibernética ajuda a proteger contra ataques direcionados a seus sistemas.
- Documentar e gerenciar ativos: precisamos conhecer os sistemas e dispositivos que devemos gerenciar e proteger adequadamente.
- Atualização e correção de sistemas: garantindo que computadores, servidores e dispositivos de rede sejam corretamente atualizados e corrigidos contra qualquer vulnerabilidade (fraqueza) conhecida.
- Configurar dispositivos de segurança preventiva: firewall e sistemas de prevenção de intrusão (IPS) são componentes críticos da segurança preventiva. Firewalls controlam o tráfego de rede que pode entrar e o que pode deixar o sistema ou a rede. O IPS bloqueia qualquer tráfego de rede que corresponda às regras atuais e assinaturas de ataque.
- Configurar dispositivos de registro e monitoramento: o registro e o monitoramento de rede adequados são essenciais para detectar atividades e intrusões maliciosas. Se um novo dispositivo não autorizado aparecer em nossa rede, devemos ser capazes de detectá-lo.

**Há muito mais na segurança defensiva. Além do acima exposto, abordaremos também os seguintes tópicos relacionados:**

- Centro de Operações de Segurança (SOC).
- Inteligência de Ameaça.
- Forense Digital e Resposta a Incidentes (DFIR).
- Análise de Malware.

# Áreas de Segurança Defensiva:

**tópicos principais relacionados à segurança defensiva:**

- Security Operations Center (SOC), onde cobrimos a Inteligência de Ameaças.
- Digital Forensics and Incident Response (DFIR), onde também cobrimos a Análise de Malware 

**Security Operations Center(SOC)**:

 
**Algumas das principais áreas de interesse para um SOC são:**

- Vulnerabilidades: Sempre que uma vulnerabilidade do sistema (fraqueza) é descoberta, é essencial corrigi-la instalando uma atualização ou patch adequado. Quando uma correção não está disponível, as medidas necessárias devem ser tomadas para evitar que um invasor a explore. Embora a correção de vulnerabilidades seja vital para um SOC, ela não é necessariamente atribuída a elas.
- Violações de políticas: Uma política de segurança é um conjunto de regras necessárias para proteger a rede e os sistemas. Por exemplo, pode ser uma violação de política se os usuários fizerem upload de dados confidenciais da empresa para um serviço de armazenamento on-line.
- Atividade não autorizada: considere o caso em que o nome de login e a senha de um usuário são roubados e o invasor os usa para entrar na rede. Um SOC deve detectar e bloquear tal evento o mais rápido possível antes que mais danos sejam feitos.Atividade não autorizada: considere o caso em que o nome de login e a senha de um usuário são roubados e o invasor os usa para entrar na rede. Um SOC deve detectar e bloquear tal evento o mais rápido possível antes que mais danos sejam feitos.
- Intrusões de rede: Não importa o quão boa seja sua segurança, sempre há uma chance de uma intrusão. Uma intrusão pode ocorrer quando um usuário clica em um link malicioso ou quando um invasor explora um servidor público. De qualquer forma, quando ocorre uma intrusão, devemos detectá-la o mais rápido possível para evitar mais danos.

 **Inteligência de Ameaça**: 

- informação que você reúne sobre inimigos reais e potenciais.
- coleta informações para ajudar a empresa a se preparar melhor contra potenciais adversários.
- conseguir uma defesa informada sobre ameaças.

**Digital Forensics and Incident Response (DFIR)**:

- Sistema de arquivos : A análise de uma imagem forense digital (cópia de baixo nível) do armazenamento de um sistema revela muitas informações, como programas instalados, arquivos criados, arquivos parcialmente substituídos e arquivos excluídos.
- Memória do sistema: Se o atacante executar seu programa malicioso na memória sem salvá-lo no disco, tirar uma imagem forense (cópia de baixo nível) da memória do sistema é a melhor maneira de analisar seu conteúdo e aprender sobre o ataque.
- Logs do sistema: cada computador cliente e servidor mantém diferentes arquivos de log sobre o que está acontecendo. Os arquivos de log fornecem muitas informações sobre o que aconteceu em um sistema. Mesmo que o atacante tente limpar seus vestígios, alguns vestígios permanecerão.
- Logs de rede: Logs dos pacotes de rede que atravessaram uma rede ajudariam a responder a mais perguntas sobre se um ataque está ocorrendo e o que ele implica.

**Resposta de Incidentes**:

- Preparação: Isso requer uma equipe treinada e pronta para lidar com incidentes. Idealmente, várias medidas são implementadas para evitar que incidentes aconteçam em primeiro lugar.
- Detecção e Análise: A equipe tem os recursos necessários para detectar qualquer incidente; além disso, é essencial analisar qualquer incidente detectado ainda mais para aprender sobre sua gravidade.
- Contenção, Erradicação e Recuperação: Uma vez que um incidente é detectado, é crucial impedi-lo de afetar outros sistemas, eliminá-lo e recuperar os sistemas afetados. Por exemplo, quando notamos que um sistema está infectado com um vírus de computador, gostaríamos de impedir (conter) o vírus de se espalhar para outros sistemas, limpar (erradicar) o vírus e garantir a recuperação adequada do sistema.
- Atividade pós-incidente: Após uma recuperação bem-sucedida, um relatório é produzido e a lição aprendida é compartilhada para evitar incidentes futuros semelhantes.Atividade pós-incidente: Após uma recuperação bem-sucedida, um relatório é produzido e a lição aprendida é compartilhada para evitar incidentes futuros semelhantes.

**Análise de Malware:**

- Um vírus é um pedaço de código (parte de um programa) que se anexa a um programa. Ele é projetado para se espalhar de um computador para outro e funciona alterando, sobrescrevendo e excluindo arquivos uma vez que infecta um computador. O resultado varia do computador tornar-se lento a inutilizável.
- Cavalo de Tróia é um programa que mostra uma função desejável, mas esconde uma função maliciosa por baixo. Por exemplo, uma vítima pode baixar um player de vídeo de um site obscuro que dá ao atacante controle total sobre seu sistema.
- Ransomware é um programa malicioso que criptografa os arquivos do usuário. A criptografia torna os arquivos ilegíveis sem saber a senha de criptografia. O invasor oferece ao usuário a senha de criptografia se o usuário estiver disposto a pagar um “resgate”.

**A análise de malware tem como objetivo aprender sobre tais programas maliciosos usando vários meios:**

- A análise estática funciona inspecionando o programa malicioso sem executá-lo. Isso geralmente requer um sólido conhecimento da linguagem de montagem (o conjunto de instruções do processador, ou seja, as instruções fundamentais do computador).
- A análise dinâmica funciona executando o malware em um ambiente controlado e monitorando suas atividades. Ele permite que você observe como o malware se comporta ao ser executado.

# Exemplo prático de segurança defensiva (continuação na tarefa): 

**cenario:** irei me passar por um analista SOC, estarei responsavel a proteger um banco. Ultilizarei uma ferramenta de Gerenciamento  de informações e eventos de segurança (SIEM).


# tarefas:

**1:** 

**Qual equipe se concentra na segurança defensiva?**
**Resposta:** Blue Team

**2:** 

**O que você chamaria de uma equipe de profissionais de segurança cibernética que monitora uma rede e seus sistemas para eventos maliciosos?**
**Resposta:** Security Operations Center

**O que representa o DFIR?** 
**Resposta:** Digital Forensics and Incident Response 

**Que tipo de malware exige que o usuário pague dinheiro para recuperar o acesso aos seus arquivos?** 
**Resposta:** ransomware

**3 Pratica (continuação exemplo pratico):** 

<img width="905" height="936" alt="{E950A676-F357-4B48-97DD-A1609E884EC6}" src="https://github.com/user-attachments/assets/6aa3e4ba-44ee-48fa-836c-171d4fa0a426" />
<img width="923" height="921" alt="{3DF133F4-2D55-430F-BF9F-0547DA02E64A}" src="https://github.com/user-attachments/assets/deea9b2d-9cd8-4600-b316-a1c100c4cfc2" />
<img width="931" height="920" alt="{32588CFF-5669-4DEF-9DDF-6AC9F57E3FA2}" src="https://github.com/user-attachments/assets/b085150f-2735-4b3b-80dc-c6125c762dd7" />
<img width="893" height="652" alt="{CEAB11B7-4932-4762-8553-4D28F4D941C5}" src="https://github.com/user-attachments/assets/afb44110-03eb-4ff2-95b3-cb02967bb4c9" />
<img width="854" height="855" alt="{79AD6296-577D-4844-A921-E033EB4A0576}" src="https://github.com/user-attachments/assets/cdbbc694-a055-4b91-8a22-d7a86f801664" />
<img width="917" height="289" alt="{7058C7E8-C131-4CB0-8C55-2C6CD1670C54}" src="https://github.com/user-attachments/assets/4f43b84b-1774-4951-b40e-27b8209ee1ff" />

**Resposta:** THM{THREAT-BLOCKED} 

# O que aprendi: 

- SOC e uma equeipe de segurança cibernetica responsaveis no monitoramento de rede e dos sisstemas para detectar eventos maliciosos.
- Inteligência de Ameaça, coleta informaçõe para lidar melhor contra adversario.
- DFIR investiga crtimes e eestabelece fatos (crimes ralacioonados a computação) 
- Malware software malicioso com diversos tipos (tipos citados em atividades acima). 
- Pratica de uma ferramenta de simulação de uma defesa realizada por  um SOC.

# Observação:

Este tema já possuía muitos conceitos importantes. Cada tópico explicou um pouco sobre sua função e atuação, o que me ajudou a entender melhor o papel do Blue Team. Como objetivo futuro é ser pentester, compreender como a defesa funciona é fundamental para o meu desenvolvimento.












