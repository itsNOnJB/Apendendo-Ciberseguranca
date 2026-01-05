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

<img width="822" height="652" alt="{55B4E9D3-7B61-4F0B-9F5E-C243917C2890}" src="https://github.com/user-attachments/assets/8ffb9c79-d2ff-4f54-8762-92c7a734e00f" />

<img width="875" height="925" alt="{1E7E1DA2-9B3A-44C2-9364-CF470094B561}" src="https://github.com/user-attachments/assets/434f98a5-0b1e-46c3-a089-e43b75fef2aa" /> 

<img width="807" height="830" alt="{B1BF9F80-E332-4963-8E32-90C34CE7F0BA}" src="https://github.com/user-attachments/assets/2ad527b2-a202-4a8e-8c69-c41878570844" /> 

<img width="867" height="935" alt="{C9873470-D81C-4767-B1A2-FC3112D2349C}" src="https://github.com/user-attachments/assets/f6c29431-a254-40bf-8af1-b0b56a5a0af3" /> 

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
