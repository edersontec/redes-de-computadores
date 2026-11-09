# 🌐 Repositório de Redes de Computadores

> Atividades práticas, pesquisas temáticas e apresentações estruturadas desenvolvidas para a disciplina de **Redes de Computadores**.

---

## 📌 Sumário de Conteúdos

1. [Visão Geral do Repositório](#-visão-geral-do-repositório)
2. [Estrutura de Pastas e Módulos](#-estrutura-de-pastas-e-módulos)
   - [01. Atividade em Grupo 1: A Revolução da Internet nos Anos 1990](#01-atividade-em-grupo-1-a-revolução-da-internet-nos-anos-1990)
   - [02. Atividade em Grupo 2: Pesquisa Aprofundada dos 10 Protocolos](#02-atividade-em-grupo-2-pesquisa-aprofundada-dos-10-protocolos)
   - [03. Atividade 3: CIDR e Máscaras de Sub-rede](#03-atividade-3-cidr-e-máscaras-de-sub-rede)
3. [Tabela Rápida de Acesso aos Arquivos](#-tabela-rápida-de-acesso-aos-arquivos)
4. [Instruções de Visualização e Compilação (Marp CLI)](#-instruções-de-visualização-e-compilação-marp-cli)
5. [Referências Bibliográficas e Normativas](#-referências-bibliográficas-e-normativas)

---

## 📖 Visão Geral do Repositório

Este repositório reúne os projetos, questionários técnicos e materiais visuais de apresentação elaborados para aprofundar os conceitos teóricos e práticos da disciplina de **Redes de Computadores**. 

Todos os materiais foram estruturados combinando:
- **Rigor Técnico e Teórico:** Baseado na literatura canônica (Kurose & Ross, Tanenbaum, Comer) e nas RFCs da IETF.
- **Apresentações em Slides Modernos:** Desenvolvidas em Markdown utilizando a engine de apresentação **[Marp](https://marp.app/)**, compiladas tanto para documentos vetoriais **PDF (16:9)** quanto para apresentações interativas **HTML**.
- **Ilustrações e Diagramas Autorais:** Fluxogramas vetoriais (SVG) e esquemas de tráfego de pacotes detalhando o funcionamento interno de protocolos.

---

## 📂 Estrutura de Pastas e Módulos

```text
redes-de-computadores/
│
├── 01-atividade-em-grupo-1/       # História da Internet: Década de 1990
│   ├── assets/                   # Fotografias históricas e imagens de arquivo
│   ├── preview/                  # Prévias dos slides gerados em PNG
│   ├── exercicio-proposto.md     # Enunciado e requisitos da atividade
│   ├── apresentacao.md           # Slides em Markdown (formato Marp)
│   ├── apresentacao.pdf          # Slides finais em PDF (17 slides)
│   └── apresentacao.html         # Apresentação interativa para navegador
│
├── 02-atividade-em-grupo-2/       # Pesquisa Aprofundada de Protocolos de Rede
│   ├── diagrams/                 # 10 Diagramas e fluxogramas vetoriais (SVG)
│   ├── preview/                  # Prévias dos 54 slides em PNG
│   ├── exercicio-proposto        # Enunciado original com a lista de protocolos
│   ├── apresentacao.md           # Slides completos em Markdown (formato Marp)
│   ├── apresentacao.pdf          # Slides finais em PDF (54 slides)
│   └── apresentacao.html         # Apresentação interativa para navegador
│
├── 03-cidr-mascara-subrede/       # CIDR e Máscara de Sub-rede (IPv4)
│   ├── exercicio.md              # Questionário com 10 questões de múltipla escolha
│   ├── apresentacao.md           # Gabarito comentado e justificativas teóricas
│   └── apresentacao.pdf          # Documento final em PDF
│
└── README.md                     # Guia e documentação unificada do repositório
```

---

### 01. Atividade em Grupo 1: A Revolução da Internet nos Anos 1990

* **Tema:** Período histórico da Internet na década de 1990.
* **Foco:** A transição de um experimento acadêmico-militar restrito para a rede mundial de computadores aberta ao público e ao comércio.
* **Tópicos Abordados:**
  1. **Linha do Tempo Cronológica (1990–1999):** Desativação da ARPANET, criação da World Wide Web no CERN, liberação do código em domínio público (1993), desativação da NSFNET (1995), Windows 95, nascimento do e-commerce, padronização do Wi-Fi (IEEE 802.11) e fundação do Google.
  2. **Marcos e Invenções Tecnológicas:**
     - A Tríade da Web: HTML (marcação estrutural), HTTP (protocolo de aplicação) e URL/URI (endereçamento global).
     - Navegadores Gráficos: NCSA Mosaic (1993) e Netscape Navigator (1994).
     - Guerra dos Navegadores, criação do CSS e nascimento do JavaScript por Brendan Eich.
     - A era da conexão discada (*Dial-Up* de 56 kbps), provedores de acesso (ISPs) e segurança criptográfica com SSL/TLS (HTTPS).
     - Mensageria instantânea (ICQ, mIRC, Webmail/Hotmail) e o algoritmo PageRank do Google.
  3. **Personagens Históricos:** Sir Tim Berners-Lee, Marc Andreessen, Brendan Eich, Linus Torvalds, Larry Page e Sergey Brin.
  4. **Impacto Atual:** Evolução para HTTP/2 e HTTP/3 (QUIC), domínio do Linux nos servidores de nuvem (AWS/Azure/GCP), comércio eletrônico trilionário e a Web como base para a Inteligência Artificial moderna.

---

### 02. Atividade em Grupo 2: Pesquisa Aprofundada dos 10 Protocolos

* **Tema:** Pesquisa estruturada sobre 10 protocolos fundamentais da pilha de redes.
* **Estrutura Padronizada:** Rigorosamente **5 slides por protocolo**, totalizando 54 slides com capa, síntese integrada e referências:
  - **Slide 1 — Identificação:** Nome oficial, sigla por extenso, camada (OSI / TCP-IP), portas padrão, RFCs e função principal.
  - **Slide 2 — Analogia:** Metáfora detalhada com uma situação concreta do cotidiano humano e a justificativa didática.
  - **Slide 3 — Ilustração:** Diagrama/fluxograma vetorial autoral em SVG ilustrando a troca de pacotes, handshakes e campos de cabeçalho.
  - **Slide 4 — Exemplo Real:** Aplicação prática no dia a dia, funcionamento na comunicação e exemplos de comandos de terminal (`arp -a`, `netstat`, `ping`, `ipconfig`, etc.).
  - **Slide 5 — Relação com Outros Protocolos:** Simbiose e dependência com protocolos de camadas adjacentes ou complementares.

#### Relação dos Protocolos Estudados:

| # | Protocolo | Camada | Função Central | Analogia do Cotidiano |
| :-: | :--- | :---: | :--- | :--- |
| **1** | **dARP / ARP** | Enlace / Rede (L2/L3) | Resolve endereço lógico IPv4 em endereço físico MAC local | Entregador chamando o nome de um morador no saguão do condomínio |
| **2** | **HTTP** | Aplicação (L7) | Requisita e transfere hipertextos e hipermídias na Web de forma *stateless* | Pedidos pontuais no balcão de uma lanchonete expressa |
| **3** | **FTP** | Aplicação (L7) | Transferência confiável de arquivos com canais de controle e dados separados | Ligar para uma transportadora que envia um caminhão dedicado |
| **4** | **TCP** | Transporte (L4) | Canal orientado à conexão, confiável, ordenado e com controle de fluxo | Livros numerados enviados por carta registrada com aviso de recebimento (AR) |
| **5** | **ICMP** | Rede (L3) | Diagnóstico, reporte de erros de roteamento e teste de conectividade | O painel de luzes de alerta do carro e os batedores na rodovia |
| **6** | **IP** | Rede (L3) | Endereçamento lógico hierárquico e roteamento *Best-Effort* pelo mundo | O sistema de endereçamento e CEP dos Correios mundiais |
| **7** | **SMTP** | Aplicação (L7) | Envio e retransmissão de mensagens de e-mail (*Push*) | Depositar uma carta na caixa coletora da calçada para triagem e entrega |
| **8** | **Telnet** | Aplicação (L7) | Emulação de terminal remoto em texto plano na porta TCP 23 | Ditar a senha do banco pelo megafone em praça pública |
| **9** | **UDP** | Transporte (L4) | Transporte sem conexão, sem confirmação e com foco em latência mínima | Transmissão de rádio ao vivo: se chia no túnel, a narração não volta |
| **10** | **NNTP** | Aplicação (L7) | Distribuição descentralizada de notícias e fóruns da USENET | Mural comunitário de avisos replicado entre blocos do campus |

---

### 03. Atividade 3: CIDR e Máscaras de Sub-rede

* **Tema:** Endereçamento IPv4, notação CIDR (*Classless Inter-Domain Routing*) e cálculo de sub-redes.
* **Conteúdo:** 10 questões analíticas comentadas passo a passo:
  - Significado da notação de prefixo de rede (ex: `/24`, `/16`, `/8`).
  - Associação binária e decimal pontuada das máscaras correspondentes (`255.0.0.0`, `255.255.0.0`, `255.255.255.0`, `255.255.255.128`).
  - Divisão de bits entre Identificador de Rede (*Net ID*) e Identificador de Host (*Host ID*).
  - Cálculo de endereços de rede, endereço de broadcast e número de hosts utilizáveis ($2^h - 2$).
  - Efeito da subdivisão de redes (passagem de `/24` para `/26`, dividindo o domínio de broadcast e ajustando a quantidade de hosts).

---

## 🚀 Tabela Rápida de Acesso aos Arquivos

| Módulo / Pasta | Enunciado | Fonte Markdown | Documento PDF | Versão Interativa |
| :--- | :---: | :---: | :---: | :---: |
| **01. Década de 1990** | [Enunciado](01-atividade-em-grupo-1/exercicio-proposto.md) | [apresentacao.md](01-atividade-em-grupo-1/apresentacao.md) | [apresentacao.pdf](01-atividade-em-grupo-1/apresentacao.pdf) | [apresentacao.html](01-atividade-em-grupo-1/apresentacao.html) |
| **02. 10 Protocolos de Rede** | [Enunciado](02-atividade-em-grupo-2/exercicio-proposto) | [apresentacao.md](02-atividade-em-grupo-2/apresentacao.md) | [apresentacao.pdf](02-atividade-em-grupo-2/apresentacao.pdf) | [apresentacao.html](02-atividade-em-grupo-2/apresentacao.html) |
| **03. CIDR e Sub-redes** | [Enunciado](03-cidr-mascara-subrede/exercicio.md) | [apresentacao.md](03-cidr-mascara-subrede/apresentacao.md) | [apresentacao.pdf](03-cidr-mascara-subrede/apresentacao.pdf) | — |

---

## 🛠️ Instruções de Visualização e Compilação (Marp CLI)

As apresentações utilizam o framework **Marp**, que permite criar slides modernos em Markdown com layout responsivo 16:9 e estilização CSS.

### Pré-requisitos
- [Node.js](https://nodejs.org/) instalado no sistema (versão 18 ou superior).
- Google Chrome ou Microsoft Edge (utilizados pelo Marp em modo *headless* para renderizar os PDFs com qualidade vetorial).

### Como Visualizar
- **PDF:** Abra os arquivos `.pdf` diretamente no leitor de PDF de sua preferência ou em qualquer navegador.
- **HTML Interativo:** Dê um duplo clique nos arquivos `.html`. Pressione `F` para entrar em modo tela cheia e utilize as setas do teclado (`←` e `→`) ou a barra de espaço para navegar entre os slides.

### Como Recompilar os Slides
Caso queira alterar o conteúdo ou o estilo dos slides no arquivo `apresentacao.md`, você pode regerar o PDF e o HTML executando os seguintes comandos no terminal:

```bash
# Para a Atividade 1:
cd 01-atividade-em-grupo-1
npx @marp-team/marp-cli apresentacao.md --pdf -o apresentacao.pdf --allow-local-files
npx @marp-team/marp-cli apresentacao.md -o apresentacao.html --allow-local-files

# Para a Atividade 2:
cd ../02-atividade-em-grupo-2
npx @marp-team/marp-cli apresentacao.md --pdf -o apresentacao.pdf --allow-local-files
npx @marp-team/marp-cli apresentacao.md -o apresentacao.html --allow-local-files
```

---

## 📚 Referências Bibliográficas e Normativas

1. **KUROSE, James F.; ROSS, Keith W.** *Redes de Computadores e a Internet: Uma Abordagem Top-Down*. 6ª e 7ª ed. São Paulo: Pearson, 2013/2017.
2. **TANENBAUM, Andrew S.; WETHERALL, David.** *Redes de Computadores*. 5ª ed. São Paulo: Pearson Prentice Hall, 2011.
3. **COMER, Douglas E.** *Interligação em Rede com TCP/IP: Princípios, Protocolos e Arquitetura*. Vol. 1. 6ª ed. Elsevier, 2015.
4. **STEVENS, W. Richard.** *TCP/IP Illustrated, Volume 1: The Protocols*. Addison-Wesley, 1994.
5. **CERN (European Organization for Nuclear Research).** *The Birth of the Web: History and Archives*. Disponível em: `<https://home.cern/science/computing/birth-web>`.
6. **IETF RFCs Oficiais:**
   - `RFC 768` – User Datagram Protocol (UDP)
   - `RFC 791` – Internet Protocol (IPv4)
   - `RFC 792` – Internet Control Message Protocol (ICMP)
   - `RFC 793` – Transmission Control Protocol (TCP)
   - `RFC 826` – Ethernet Address Resolution Protocol (ARP)
   - `RFC 854` – Telnet Protocol Specification
   - `RFC 959` – File Transfer Protocol (FTP)
   - `RFC 977` / `RFC 3977` – Network News Transfer Protocol (NNTP)
   - `RFC 1945` / `RFC 2616` / `RFC 9114` – Hypertext Transfer Protocol (HTTP/1.0, 1.1 e 3)
   - `RFC 4632` – Classless Inter-domain Routing (CIDR)
   - `RFC 5321` – Simple Mail Transfer Protocol (SMTP)
