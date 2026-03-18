<div align="center">

<img src="https://raw.githubusercontent.com/ViniciusSantanaLive/ProjectYokaiOS/develop/public/logo.png" width="120" alt="YokaiOS Logo"/>

# YokaiOS

**Windows optimizer para gamers e power users.**  
Remove bloatware, aumenta performance, protege privacidade — tudo com um clique.

[![GitHub release](https://img.shields.io/github/v/release/ViniciusSantanaLive/YokaiOS-Downloads?style=flat-square&color=6366f1)](https://github.com/ViniciusSantanaLive/YokaiOS-Downloads/releases/latest)
[![Platform](https://img.shields.io/badge/platform-Windows%2010%2F11-blue?style=flat-square)](https://github.com/ViniciusSantanaLive/YokaiOS-Downloads/releases/latest)
[![License](https://img.shields.io/badge/license-MIT-green?style=flat-square)](LICENSE)

[⬇️ Download YokaiOS](#-download-yokaios) • [💿 ISOs Customizadas](#-isos-customizadas) • [📖 Guia de Uso](#-guia-de-uso)

</div>

---

## ⬇️ Download YokaiOS

Baixe a versão mais recente na página de [Releases](https://github.com/ViniciusSantanaLive/YokaiOS-Downloads/releases/latest).

| Arquivo | Descrição |
|---|---|
| `YokaiOS_x.x.x_x64-setup.exe` | Instalador NSIS (recomendado) |
| `YokaiOS_x.x.x_x64_portable.exe` | Versão portátil, sem instalação |

> ⚠️ **Requer execução como Administrador.** As otimizações modificam o registro e serviços do Windows.

---

## 💿 ISOs Customizadas

ISOs do Windows com a experiência inicial simplificada — sem as telas chatas de setup, sem obrigatoriedade de conta Microsoft, sem o Windows Defender atrapalhando.

> **Use o [Free Download Manager](https://www.freedownloadmanager.org/)** para baixar as ISOs mais rápido com suporte a retomada de download.

### Windows 11 — YokaiOS Edition

| Versão | Link |
|---|---|
| Windows 11 YokaiOS | [⬇️ Baixar win11-YokaiOS](#) |

### Windows 10 — YokaiOS Edition

| Versão | Link |
|---|---|
| Windows 10 YokaiOS | 🔜 Em breve |

### O que foi removido/modificado nas ISOs

- ✅ **Setup simplificado** — sem telas de permissões, coleta de dados e configurações inúteis
- ✅ **Conta Microsoft opcional** — entra direto com conta local
- ✅ **Windows Defender desativado** — use o antivírus da sua preferência (Malwarebytes, Kaspersky, etc.) ou nenhum
- ✅ **Bloatware removido** — sem apps de terceiros pré-instalados
- ✅ **Telemetria desativada** — sem coleta de dados desde o primeiro boot

> **Nota:** A ISO não substitui uma licença válida do Windows. Ative normalmente com sua chave ou pelo YokaiOS usando a aba **Tools → MAS (Microsoft Activation Scripts)**.

---

## 📖 Guia de Uso

### Como funciona

1. Abra o YokaiOS como Administrador
2. Selecione as otimizações que deseja aplicar
3. Clique em **Apply** — ou use os **Presets** para aplicar grupos pré-configurados
4. Algumas otimizações requerem reinicialização — o app avisa quando necessário

---

### 🗑️ Debloat

Remove apps e funcionalidades desnecessárias que consomem RAM, CPU e espaço em disco.

| Item | O que faz |
|---|---|
| **3rd Party Apps** | Remove bloatware de terceiros pré-instalados (Netflix, Spotify, Candy Crush, Facebook, etc.) |
| **Media Extensions** | Remove extensões de mídia desnecessárias (HEIF, VP9, WebP, HEVC, etc.) |
| **Microsoft Apps** | Remove apps Microsoft não essenciais (Solitaire, Teams, Skype, Outlook, Maps, etc.) |
| **Xbox** | Remove todos os apps Xbox e define serviços como manual. Previne reinstalação automática |
| **Consumer Features** | Desativa instalação silenciosa de apps e sugestões automáticas do Windows |
| **Hyper-V** | Desativa virtualização Hyper-V. Aumenta performance em jogos e apps nativos |
| **Internet Explorer** | Remove o IE legado via DISM |
| **Fax & Scan** | Remove o serviço de fax e digitalização |
| **Media Player** | Remove o Windows Media Player legado |
| **Hide AI Button** | Remove o botão do Copilot da barra de tarefas |
| **AI AppX Packages** | Remove pacotes Appx de IA (Copilot, Recall, WindowsAiFoundation) |
| **Copilot** | Remove o Windows Copilot completamente — app, extensão shell e 9 chaves de registro |
| **Recall** | Desativa o Windows Recall via DISM, remove tasks agendadas e bloqueia via registro |
| **Notepad AI** | Remove o botão de reescrita com IA do Bloco de Notas |
| **AI Files** | Remove arquivos residuais de IA do sistema (WindowsApps, LocalAppData, SystemApps) |
| **Microsoft Store** | Remove a Microsoft Store completamente ⚠️ |
| **Store Auto Updates** | Desativa atualizações automáticas de apps pela Store |
| **OneDrive** | Desinstala o OneDrive completamente, move arquivos para pasta local e limpa o Explorer |
| **Debloat Edge** | Aplica 26 políticas no Edge: desativa shopping, sidebar, wallet, Copilot, rewards, etc. |
| **Remove Edge** | Remove o Microsoft Edge completamente ⚠️ Requer reinicialização |
| **Widgets** | Remove o painel de Widgets e previne reinstalação |
| **Taskbar Widgets** | Remove widgets, botão Task View e feeds de notícias da barra de tarefas |
| **Disable Windows Update** | Desativa o Windows Update completamente ⚠️ Use com cautela |

---

### ⚡ Performance

Ajustes de sistema para reduzir latência, aumentar FPS e diminuir processos em background.

**DNS**

| Item | O que faz |
|---|---|
| **Google DNS** | Define DNS para 8.8.8.8 / 8.8.4.4 na interface ativa |
| **Cloudflare DNS** | Define DNS para 1.1.1.1 / 1.0.0.1 |
| **OpenDNS** | Define DNS para 208.67.222.222 / 208.67.220.220 |
| **Quad9 DNS** | Define DNS seguro para 9.9.9.9 / 149.112.112.112 |
| **AdGuard DNS** | Define DNS com bloqueio de anúncios para 94.140.14.14 / 94.140.15.15 |

**Plano de Energia**

| Item | O que faz |
|---|---|
| **Balanced** | Ativa o plano Balanceado (padrão) |
| **High Performance** | Ativa o plano Alto Desempenho |
| **Ultimate Performance** | Ativa o plano Máximo Desempenho + desativa PowerThrottling e Connected Standby |

**Otimizações**

| Item | O que faz |
|---|---|
| **Services to Manual** | Define ~130 serviços como Manual e desativa 10 serviços de telemetria. Maior redutor de processos |
| **Disable Transparency** | Desativa efeitos de transparência (reduz overhead de GPU) |
| **Disable HAGS** | Desativa Hardware Accelerated GPU Scheduling. Requer reinicialização |
| **Mouse Delay** | Remove delay de hover/menu e define SystemResponsiveness para 0% |
| **Limit Defender** | Limita o uso de CPU do Windows Defender a 25% durante scans |
| **Core Isolation** | Desativa VBS, HVCI e Credential Guard. +5-10% FPS em jogos ⚠️ Requer reinicialização |
| **Storage Sense** | Desativa a limpeza automática do Storage Sense |
| **Disable Prefetch** | Para e desativa o SysMain (Superfetch). Reduz I/O em SSDs |
| **Disable Search** | Para e desativa a indexação do Windows Search. Reduz I/O |
| **Disable Hibernation** | Desativa hibernação e remove hiberfil.sys liberando espaço |
| **SvcHost Split** | Força merge de processos svchost. Reduz de 20+ para 3-4 processos. Requer reinicialização |
| **Optimize NTFS** | Desativa timestamps de último acesso, nomes 8.3 e otimiza uso de memória |
| **Paging Executive** | Mantém kernel e drivers na RAM, nunca paginado para disco. Requer reinicialização |
| **Auto Maintenance** | Desativa tarefas de manutenção automática em background |
| **Fault Tolerant Heap** | Desativa o monitoramento FTH que gera overhead |
| **Disable Nagle** | Desativa o algoritmo Nagle em todas as interfaces TCP. Reduz latência de rede |
| **MMCSS Games** | Define GPU Priority=8, CPU Priority=6 e Scheduling=High para jogos |
| **Win32 Priority** | Define Win32PrioritySeparation para 0x26 — máximo boost para apps em foreground |
| **Network Overhead** | Desativa LLMNR, throttling SMB e overhead NetBIOS |
| **Telemetry Services** | Para e desativa DiagTrack, TrkWks, PcaSvc, WerSvc e outros serviços de telemetria |
| **Large System Cache** | Otimiza o gerenciador de memória para aplicações (ideal para gaming). Requer reinicialização |
| **Disable Modern Standby** | Desativa Connected Standby, Modern Standby e Fast Startup. Requer reinicialização |
| **Disable Superfetch Complete** | Para SysMain + desativa todas as tasks de manutenção relacionadas |
| **Disable WER Complete** | Desativa Windows Error Reporting completamente — WerFault e Dr. Watson |
| **Timer Resolution** | Otimiza resolução do timer do sistema. Desativa dynamic tick. Requer reinicialização |
| **Limit Runtime Broker** | Desativa apps em background globalmente. Reduz instâncias de RuntimeBroker |
| **Limit DllHost Triggers** | Reduz triggers de COM Surrogate e thumbnail handlers |
| **Maintenance Tasks** | Desativa ~27 tasks agendadas de manutenção que acordam processos em background |

---

### 🔒 Privacy

Revoga permissões de apps e desativa funcionalidades de rastreamento do Windows.

| Item | O que faz |
|---|---|
| **Privacy Consent** | Revoga todas as permissões de acesso de apps (localização, conta, contatos, etc.) |
| **Pause Updates** | Estende o limite de pausa do Windows Update para ~20 anos |
| **Cloud Sync** | Desativa toda sincronização em nuvem (configurações, credenciais, temas, browser) |
| **Activity History** | Desativa feed de atividades, publicação e upload de atividades |
| **Notification Tray** | Desativa o centro de notificações e notificações toast |
| **Auto Map Downloads** | Desativa download automático de mapas offline |
| **Remove Default0 User** | Remove o usuário oculto `defaultuser0` |
| **Lockscreen Camera** | Bloqueia acesso à câmera pela tela de bloqueio |
| **Biometrics** | Desativa Windows Hello e biometria |
| **WiFi Sense** | Desativa conexão automática a redes Wi-Fi compartilhadas |
| **Cloud Clipboard** | Desativa histórico e sincronização de área de transferência |
| **Screen Recording** | Nega acesso de gravação de tela em background para apps |
| **Voice Activation** | Desativa ativação por voz ("Hey Cortana") |
| **Location** | Nega acesso à localização para todos os apps |
| **Account Info** | Nega acesso a informações de conta para apps |
| **Motion** | Nega acesso a sensores de movimento |
| **Trusted Devices** | Desativa informações de pareamento de dispositivos confiáveis |
| **Contacts** | Nega acesso a contatos |
| **Calendar** | Nega acesso ao calendário |
| **Email** | Nega acesso ao email |
| **Tasks** | Nega acesso a tarefas |
| **Radios** | Nega controle de rádio (Bluetooth, etc.) para apps |
| **System Access** | Nega acesso a diagnósticos do sistema |
| **Call History** | Nega acesso ao histórico de chamadas |
| **Messaging** | Nega acesso a mensagens |
| **Notification Access** | Nega acesso a notificações para apps de terceiros |
| **Diagnostics** | Nega acesso a diagnósticos de apps |
| **Phone Access** | Nega acesso a funcionalidades de telefone |
| **Camera** ⚠️ | Nega acesso à webcam para **todos** os apps. Discord/Zoom não funcionarão |
| **Microphone** ⚠️ | Nega acesso ao microfone para **todos** os apps. Voice chat não funcionará |
| **Recordings** | Nega acesso a gravações de áudio |
| **Screenshot Border** | Nega captura de tela sem borda para apps |
| **AI Generation** | Nega acesso a recursos de geração de IA para apps |

---

### 🎮 Gaming

Otimizações específicas para reduzir input lag e melhorar a experiência em jogos.

| Item | O que faz |
|---|---|
| **Fullscreen Optimizations** | Desativa FSO e força fullscreen exclusivo real em DX11/DX12. Reduz input lag |
| **Mouse Acceleration** | Desativa aceleração do mouse e define curva 1:1 perfeita para raw input |
| **Game Mode** | Desativa o Game Mode do Windows. Reduz micro-stuttering causado pelo gerenciamento de recursos |
| **Game Bar** | Desativa completamente o Xbox Game Bar — overlay, painel de início e DVR |
| **Captures** | Desativa toda captura de gameplay — vídeo, áudio, cursor e buffer histórico |
| **MSI Mode** | Ativa Message Signaled Interrupts para GPU, rede, USB e storage. Reduz input lag de hardware. Requer reinicialização |

---

### 📡 Telemetry

Desativa coleta de dados do Windows e de softwares de terceiros.

| Item | O que faz |
|---|---|
| **Windows Telemetry** | Desativa telemetria principal — 9 tasks, 4 serviços e 35 chaves de registro |
| **WUpdate Telemetry** | Desativa telemetria do Windows Update e entrega P2P |
| **Search Telemetry** | Desativa 24 chaves de telemetria do Windows Search (Bing, Cortana, cloud, histórico) |
| **Office Telemetry** | Desativa telemetria do Office 15/16 — 18 chaves e 6 tasks agendadas |
| **App Experience** | Desativa coleta de dados de compatibilidade de aplicativos — 5 tasks |
| **Feedback Data** | Desativa notificações e coleta de feedback do Windows |
| **Handwriting Data** | Desativa coleta de dados de escrita à mão e digitação |
| **Windows DRM** | Desativa acesso à internet do Windows DRM |
| **Cloud Speech** | Desativa reconhecimento de voz em nuvem |
| **Targeted Ads** | Desativa anúncios direcionados — 17 chaves (advertising ID, Spotlight, tailored experiences) |
| **Block Adobe Network** | Adiciona servidores de telemetria da Adobe ao arquivo hosts |
| **NVIDIA Telemetry** | Desativa telemetria NVIDIA — 5 chaves de registro e 3 tasks agendadas |
| **VS/VSCode Telemetry** | Desativa telemetria do Visual Studio e VS Code — 13 chaves (VS 14-17, IntelliCode) |
| **Media Player Telemetry** | Desativa rastreamento do Windows Media Player |
| **PowerShell Telemetry** | Define variável de ambiente `POWERSHELL_TELEMETRY_OPTOUT=1` de forma persistente |
| **CCleaner Telemetry** | Desativa monitoramento e telemetria do CCleaner — 12 chaves |
| **Google Updates** | Desativa serviços e tasks de atualização em background do Google Chrome |
| **Adobe Updates** | Desativa serviços e tasks de atualização em background da Adobe |

---

### 🔧 Misc

Ajustes de usabilidade e preferências do sistema.

| Item | O que faz |
|---|---|
| **Classic Right-Click Menu** | Restaura o menu de contexto do Windows 10 (sem o "Mostrar mais opções") |
| **Disable MPO** | Desativa MultiPlane Overlay. Corrige flickering, stuttering e crashes em jogos |
| **End Task in Menu** | Adiciona "Finalizar Tarefa" ao menu de contexto da barra de tarefas |
| **Taskbar Left** | Alinha os ícones da barra de tarefas à esquerda (estilo Windows 10) |
| **Disable NumLock** | Desativa a ativação automática do NumLock na inicialização |
| **Dark Mode** | Ativa o modo escuro global para apps e sistema |
| **File Extensions** | Exibe extensões de arquivo no Explorer |
| **Sticky Keys** | Desativa atalhos de Sticky Keys, Toggle Keys e Filter Keys (evita popups acidentais em jogos) |
| **Snap Flyout** | Desativa o flyout de snap layout ao passar o mouse no botão maximizar |
| **Detailed BSOD** | Exibe parâmetros detalhados na tela azul para facilitar diagnóstico |
| **Verbose Logon** | Exibe mensagens de status detalhadas durante login/logoff/desligamento |

---

### 🛡️ Services

Painel de controle de serviços do Windows. Permite iniciar, parar, definir como Manual ou Desativado individualmente — sem precisar abrir o `services.msc`.

---

### 🛠️ Tools

| Item | O que faz |
|---|---|
| **Clean Temp** | Limpa arquivos temporários do sistema e do usuário |
| **Disk Cleanup** | Executa o limpador de disco do Windows |
| **Empty Recycle Bin** | Esvazia a lixeira |
| **Create Restore Point** | Cria um ponto de restauração do sistema antes de aplicar otimizações |
| **DISM** | Executa `DISM /RestoreHealth` para reparar a imagem do Windows |
| **SFC** | Executa `sfc /scannow` para verificar e reparar arquivos de sistema |
| **Clear Browser History** | Limpa histórico, cache e cookies dos principais browsers |
| **Reset Network** | Reseta configurações de rede (Winsock, DNS, IP) |
| **MAS** | Executa o Microsoft Activation Scripts para ativação do Windows |

---

### 📦 Install

Instalação rápida de softwares essenciais via winget.

**Browsers:** Brave, Chrome, LibreWolf, Zen  
**Compressão:** 7-Zip, NanaZip, WinRAR  
**Gaming:** Steam, Epic Games, Borderless Gaming  
**Utilitários:** OBS, Discord, VoiceMeeter, Stremio, Revo Uninstaller, UniGetUI, Notepad++, StartAllBack  
**Hardware:** CPU-Z, GPU-Z, HWiNFO, HWMonitor, MSI Afterburner  
**Drivers:** DDU, NVCleanstall, NVIDIA GeForce Experience, AMD Chipset, Intel DSA  
**Dev:** VS Code, Git, Node.js, Python, Postman, Docker, Rust, Cursor, VSCodium, Visual Studio 2022  

---

### 🔄 Update

Verifica e instala atualizações do YokaiOS automaticamente. Exibe changelog da versão disponível e permite atualizar com um clique, sem precisar baixar manualmente.

---

## ⚠️ Avisos

- Sempre crie um **ponto de restauração** antes de aplicar otimizações (disponível na aba Tools)
- Itens marcados com ⚠️ são irreversíveis ou têm impacto significativo — leia a descrição antes de aplicar
- As ISOs customizadas são para uso pessoal. Mantenha sua licença do Windows válida

---

<div align="center">

Feito com 🔥 por [ViniciusSantanaLive](https://github.com/ViniciusSantanaLive)

</div>
