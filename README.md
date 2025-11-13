📝 PARTE 2: README.md PRONTO PARA USO NO GITHUB

# 💻 Simulação de Malware com Python (Educacional)

> Projeto criado para fins educacionais, com o objetivo de estudar o funcionamento de ameaças digitais (ransomware e keylogger) em ambiente **controlado** e de forma **ética e segura**.

## 🎯 Objetivos

- Simular o comportamento básico de ransomware e keylogger.
- Demonstrar como essas ameaças funcionam internamente.
- Refletir sobre como nos defender de ataques reais.
- Desenvolver portfólio técnico em cibersegurança.

---

## 📁 Estrutura do Projeto

```bash
projeto-malware-simulado/
│
├── samples/                 # Arquivos alvo da simulação de ransomware
├── backup_simulado/        # Backup dos arquivos originais
├── images/                 # Capturas de tela (opcional)
├── ransomware_simulado.py  # Script simulando ataque ransomware
├── keylogger_simulado.py   # Script simulando keylogger
├── log_simulado.txt        # Log simulado de teclas
├── README_RESCUE.txt       # Mensagem de "resgate" gerada
└── README.md               # Este documento


🔐 Ransomware Simulado
Como funciona:

Criptografa arquivos .txt em uma pasta simulada.

Armazena backup seguro antes da criptografia.

Gera uma mensagem de resgate fictícia.

Pode ser revertido com a função restaurar_arquivos().

Segurança:

✅ Não realiza criptografia real e não danifica arquivos do sistema.
✅ Não se espalha nem se comunica externamente.

🕵️ Keylogger Simulado
Como funciona:

Simula eventos de teclas pré-definidas.

Gera log local (log_simulado.txt).

Simula envio por email (sem SMTP real).

Segurança:

✅ Não captura teclas reais.
✅ Não envia dados pela internet.
✅ Totalmente educativo.


🔁 1. DIAGRAMA DE FLUXO — Ataque vs Defesa

Vou gerar uma imagem com o seguinte fluxo:

Ransomware Simulado:

[Usuário Executa Script] 
     ↓
[Varre arquivos na pasta /samples]
     ↓
[Backup dos arquivos]
     ↓
[“Criptografia” Base64 dos arquivos]
     ↓
[Geração da Mensagem de Resgate]

Keylogger Simulado:

[Script simula eventos de tecla]
     ↓
[Armazena log em log_simulado.txt]
     ↓
[Simula envio por email]


Defesas Correspondentes:

[Antivírus / Antimalware] ← Análise comportamental
[Firewall] ← Bloqueia comunicação de saída
[Backup] ← Restauração dos dados reais
[Sandbox] ← Execução segura para testes
[Conscientização] ← Evita execução do malware


🧠 Reflexão: Como nos defender de malwares reais?
1. 🔍 Antivírus & Antimalware

Detecção baseada em comportamento e assinaturas.

Heurística para detectar variantes.

2. 🔥 Firewall

Impede comunicação de malwares com C2.

Bloqueia tráfego não autorizado.

3. 🧪 Sandboxing

Análise de arquivos suspeitos sem afetar o sistema.

Uso de VMs para teste de arquivos.

4. 🧠 Conscientização do Usuário

Evitar clicar em links ou anexos desconhecidos.

Verificar a autenticidade de e-mails.

Treinamento recorrente.

5. 💾 Backup

Manter backups offline ou na nuvem.

Verificar integridade dos backups.

Automatizar e testar recuperação.

⚠️ Aviso Legal

Este projeto é estritamente para fins educacionais.
Não use estes conhecimentos de forma maliciosa ou fora de ambientes autorizados.
A prática de qualquer código malicioso em sistemas reais sem consentimento é crime.

🛠️ Tecnologias

Python 3

Base64

Simulações locais seguras

Git e GitHub

✍️ Autor

Feito por Paulo Moraes


