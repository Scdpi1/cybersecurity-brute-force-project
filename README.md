# cybersecurity-brute-force-project
"Projeto de simulação de ataques de força bruta com Kali Linux e Medusa"
# Projeto de Simulação de Ataques de Força Bruta

[![Kali Linux](https://img.shields.io/badge/Kali_Linux-557C94?style=for-the-badge&logo=kalilinux&logoColor=white)](https://www.kali.org/)
[![Medusa](https://img.shields.io/badge/Medusa-FF6B6B?style=for-the-badge&logo=security&logoColor=white)](http://foofus.net/goons/jmk/medusa/medusa.html)
[![VirtualBox](https://img.shields.io/badge/VirtualBox-183A61?style=for-the-badge&logo=virtualbox&logoColor=white)](https://www.virtualbox.org/)

# Descrição
Projeto prático desenvolvido para o desafio DIO, demonstrando técnicas de força bruta utilizando Kali Linux e Medusa contra ambientes vulneráveis controlados (Metasploitable 2 e DVWA).

# Objetivos do Projeto
-  Configurar ambiente de laboratório seguro com VMs
-  Executar ataques de força bruta em serviços FTP, Web (DVWA) e SMB
-  Documentar processos técnicos e resultados obtidos
-  Propor medidas eficazes de mitigação

# Tecnologias Utilizadas
- **Kali Linux** - Distribuição para testes de penetração
- **Medusa** - Ferramenta de força bruta paralelizada
- **Metasploitable 2** - Ambiente vulnerável deliberadamente
- **DVWA (Damn Vulnerable Web Application)** - Aplicação web vulnerável
- **VirtualBox** - Plataforma de virtualização
- **Nmap** - Ferramenta de descoberta de rede
- **Enum4linux** - Enumeração de serviços SMB

#Estrutura do Projeto
cybersecurity-brute-force-project/
├── README.md
├── LICENSE
├── .gitignore
├── wordlists/
│ ├── ftp_wordlist.txt
│ ├── web_users.txt
│ ├── web_passwords.txt
│ └── common_passwords.txt
├── scripts/
│ ├── setup_environment.sh
│ ├── enumeration_scan.sh
│ └── mitigation_recommendations.sh
├── images/
│ └── placeholders.md
└── docs/
├── technical_report.md
├── mitigation_strategies.md
└── lessons_learned.md
