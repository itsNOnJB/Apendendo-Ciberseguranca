# O que é segurança ofensiva? 
- simular ataques em ambientes controlados 
- explorar vulnerabilidades para fins de teste 
- identificar falhas antes que atacantes reais explorem 
# tive uma pergunta simples nessa tarefa 1: 
Qual das opções a seguir representa melhor o processo em que você simula as ações de um hacker para encontrar vulnerabilidades em um sistema? 

**resposta**: segurança ofensiva 
# Hackeando sua primeira máquina (simulação): 

**ferramenta que vou ultilizar**: 

- maquina virtual do tryhackme 
- terminal do linux 
- site FakeBank 

# pratica: 
**Print de passsos**:

<img width="872" height="862" alt="{D4CE90FF-35F4-4CE4-8BDD-18A84D792F06}" src="https://github.com/user-attachments/assets/39260dc5-1619-4d46-844c-45399b964325" />

Finalizando a tarefa 2 tive a resposta da questão 

**Resposta**: BANK-HACKED 

# Comandos usdos: 

- gobuster -u http://fakebank.thm -w wordlist.txt dir 
- url do site: http://fakebank.thm/bank-transfer 

# o que aprendi: 
- sistemas possuem fragilidades e podem ser exploradas 
- uma varredura me revelou uma fragilidade isso me mostra como é importante manter uma plataforma segura. 

# impacto se isso tivesse sido real: 
- impacto financeiro para a empresa 
- perda de confiança com cliente 
- riscos para empresa 
# mitigação: 
- verificar pemissão do usuario 
- validar usuário no servidor 
- alerta de algo suspeito
