## Projetos

**AVISO: Repositórios em reestruturação. Para mais detalhes sobre os projetos, entre em contato.**

**[Motor de Relatórios Web](https://github.com/lfcarrega/reports-engine)** (AutoHotkey / T-SQL / JavaScript)  
Ferramenta desktop para geração de relatórios a partir de bases SQL Server, com interface web servida localmente via Caddy Server. Executa consultas T-SQL parametrizadas por data, usuário e loja, e exibe os resultados em tabelas interativas com filtros e exportação para CSV, XLSX, PDF e HTML.

**[Gerenciador de Dispositivos USB para VMs](https://github.com/lfcarrega/libvirt-helper)** (Python / Libvirt API)  
Ferramenta CLI em Python para hot-plug de dispositivos USB em máquinas virtuais KVM/QEMU sem edição manual de XML. Integra com a API do Libvirt e oferece menus interativos para seleção de domínios e dispositivos.

**[Orquestrador de GPU Passthrough para Virtualização](https://github.com/lfcarrega/gpu-passthrough-manager)** (Bash / Libvirt / VFIO)  
Script de automação para transferência de GPU entre host Linux e VMs Windows via VFIO, gerenciando o ciclo completo de detach/reattach de dispositivos PCI e conexão via Moonlight/Sunshine.

**[Provisionador automatizado de VMs Windows](https://github.com/lfcarrega/windows-vm-provisioner)** (Bash / QEMU / KVM / WinPE)
Pipeline completo de criação de VMs Windows via QEMU/KVM: geração de ISO WinPE customizada com UEFI, TPM emulado, aplicação de imagem via DISM com injeção de drivers VirtIO, criptografia de disco com LUKS em LVM thin pool e instalação desassistida via Unattend.xml.

**[Homelab & Automação de Infraestrutura](https://github.com/lfcarrega/gentoo-installer)** (Caddy / Docker / Incus / Python / DNS / Linux / WireGuard / IaC)
Desenvolvimento de uma stack completa de Infraestrutura como Código (IaC) para automação e gerenciamento de servidores domésticos. O projeto engloba scripts em Python para particionamento, criptografia e bootstrap do Gentoo Linux, integrados a playbooks Ansible para a configuração pós-instalação de serviços essenciais. A infraestrutura conta com proxy reverso Caddy (com TLS automático), redes seguras via VPN WireGuard, DNS privado criptografado (dnscrypt-proxy + Pi-hole) e compartilhamento de arquivos via Samba/RSYNC, centralizando segurança, privacidade e deploy automatizado de serviços.

**EM ANDAMENTO - Infraestrutura Windows Server** (Windows Server 2025 / AD / KVM / DNS)
Simulação de ambiente corporativo com políticas de grupo (GPO), autenticação centralizada e gestão de usuários para fins de estudo, são duas máquinas virtuais: um DC principal e um membro de domínio com Windows 11.
