## Projetos

**[Motor de Relatórios Web](https://github.com/lfcarrega/reports-engine)** (AutoHotkey / T-SQL / JavaScript)  
Ferramenta desktop para geração de relatórios a partir de bases SQL Server, com interface web servida localmente via Caddy Server. Executa consultas T-SQL parametrizadas por data, usuário e loja, e exibe os resultados em tabelas interativas com filtros e exportação para CSV, XLSX, PDF e HTML.

**[Gerenciador de Dispositivos USB para VMs](https://github.com/lfcarrega/libvirt-helper)** (Python / Libvirt API)  
Ferramenta CLI em Python para hot-plug de dispositivos USB em máquinas virtuais KVM/QEMU sem edição manual de XML. Integra com a API do Libvirt e oferece menus interativos para seleção de domínios e dispositivos.

**[Orquestrador de GPU Passthrough para Virtualização](https://github.com/lfcarrega/gpu-passthrough-manager)** (Bash / Libvirt / VFIO)  
Script de automação para transferência de GPU entre host Linux e VMs Windows via VFIO, gerenciando o ciclo completo de detach/reattach de dispositivos PCI e conexão via Moonlight/Sunshine.

**[Provisionador automatizado de VMs Windows](https://github.com/lfcarrega/windows-vm-provisioner)** (Bash / QEMU / KVM / WinPE)
Pipeline completo de criação de VMs Windows via QEMU/KVM: geração de ISO WinPE customizada com UEFI, TPM emulado, aplicação de imagem via DISM com injeção de drivers VirtIO, criptografia de disco com LUKS em LVM thin pool e instalação desassistida via Unattend.xml.

**Homelab com stack de serviços self-hosted** (Caddy / Docker / Incus / Python / REST API / Rsync / SAMBA / Svelte / WireGuard)
Infraestrutura doméstica com múltiplos serviços containerizados (Docker dentro do Incus) atrás de reverse proxy Caddy com TLS próprio e CA interna. Roteamento por subdomínio, VPN WireGuard para acesso remoto seguro, DNS privado com dnscrypt-proxy, compartilhamento de arquivos com RSYNC e SAMBA. Dashboard de monitoramento em Svelte e API com Python+FastAPI.

**EM ANDAMENTO - Infraestrutura Windows Server** (Windows Server 2025 / AD / KVM / DNS)
Simulação de ambiente corporativo com políticas de grupo (GPO), autenticação centralizada e gestão de usuários para fins de estudo, são duas máquinas virtuais: um DC principal e um membro de domínio com Windows 11.
