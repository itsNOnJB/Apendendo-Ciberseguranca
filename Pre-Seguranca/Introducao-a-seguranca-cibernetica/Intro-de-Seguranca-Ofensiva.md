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

<img width="729" height="479" alt="{E6FFE7E8-298A-46D0-A2C1-A4AE0C1767C2}" src="https://github.com/user-attachments/assets/2f361100-34c3-43a1-9517-99fc9a7e5924" />

<img width="868" height="886" alt="{C9FEDCB0-71F8-44F3-9ECF-A81E367A359C}" src="https://github.com/user-attachments/assets/8dd5a7aa-8d94-4749-95d1-880838d47981" />

<img width="872" height="837" alt="{00085FAC-B323-40A6-92A1-A5A19E4BD1B1}" src="https://github.com/user-attachments/assets/f88a5aae-dcd9-4c4d-860a-22c6f4456aad" />

<img width="872" height="753" alt="{9DA9C965-95CF-44E7-B657-3FE6C2782FF3}" src="https://github.com/user-attachments/assets/f6b5a7c4-7589-455f-b6e2-bfc6678b9d78" />

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
