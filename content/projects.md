---
title: "Projetos"
---

#### [Motor de Relatórios Web](https://github.com/lfcarrega/reports-engine) <span style="float: right;">AutoHotkey/SQL/JavaScript</span>
- Ferramenta desktop para geração de relatórios a partir do SQL Server, servindo uma interface web local criada com a biblioteca JavaScript Tabulator. Executa consultas parametrizadas e exporta resultados para CSV, XLSX, PDF e HTML.
#### [Provisionador Windows](https://github.com/lfcarrega/windows-vm-provisioner) <span style="float: right;">Bash/Go/PowerShell/Windows</span>
- Alternativa ao Microsoft MDT para deployment automatizado. Gera uma ISO WinPE customizável com agente em Go para execução de scripts de provisionamento PowerShell pós-instalação.
#### [Homelab](https://github.com/lfcarrega/gentoo-installer) <span style="float: right;">Infraestrutura/IaC</span>
- Infraestrutura como Código (IaC) para provisionamento e automação de servidores locais. Inclui deploys automatizados via Ansible de serviços como proxy reverso Caddy, VPN WireGuard e containers Docker.
- Montagem e manutenção de servidor doméstico com hardware reaproveitado e adaptado (troca de placa-mãe por incompatibilidade, uso de memória de notebook via adaptador, upgrade de armazenamento com NVMe dedicado e NAS com SSDs/HDDs reaproveitados).
- Remoção do Intel Management Engine via ME Cleaner, com regravação de flash SPI por gravador externo (CH341), por questão de segurança em firmware desatualizado (UEFI de 2017).
- Automatizei ajuste de variáveis de firmware UEFI (ACPI, ASPM, PCIe, SGX) via script UEFI Shell com a ferramenta setup_var, otimizando desempenho e estabilidade em uso contínuo como servidor.
- Virtualização e containerização com Gentoo Linux como base, VM ArchLinux e múltiplos containers LXC (Incus), incluindo ambiente Docker aninhado.
