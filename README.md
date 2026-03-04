# e-VTU — Plataforma Web3 de Mobilidade Acadêmica

![e-VTU Web3](https://img.shields.io/badge/e--VTU-Web3%20Platform-blue?style=flat-square)
![License](https://img.shields.io/badge/License-MIT-green?style=flat-square)
![Status](https://img.shields.io/badge/Status-Active-brightgreen?style=flat-square)

**e-VTU** é uma plataforma inovadora que une educação, cultura e tecnologia Web3 para democratizar o acesso ao ensino superior nos municípios do Rio Grande do Sul.

## 🎯 Visão Geral

O **Fórum Acadêmico RS** iniciou o programa e-VTU como um movimento de auto-organização estudantil, transformando-o em um instrumento de fortalecimento comunitário que conecta educação, políticas públicas e transformação social.

### Três Eixos Estratégicos

- **Educação e Mobilidade Acadêmica:** Ambiente virtual que viabiliza mobilidade entre municípios, reduzindo barreiras físicas e financeiras
- **Cultura e Cidadania:** Integração de processos criativos, formação cidadã e participação democrática
- **Tecnologia e Inclusão Social:** Infraestrutura descentralizada, software livre e soberania digital das comunidades

## 🏗️ Arquitetura Técnica

A plataforma é construída em **4 camadas** utilizando exclusivamente ferramentas de software livre:

| Camada | Tecnologia | Função |
|--------|-----------|--------|
| **Infraestrutura** | Geth (Go-Ethereum) | Nó Ethereum descentralizado |
| **Lógica de Negócio** | Solidity + Truffle | Contratos inteligentes |
| **Integração** | Web3.js / Ethers.js | Ponte front-end ↔ blockchain |
| **Interface** | React + TypeScript + TailwindCSS | Aplicação web responsiva |

## 📋 Contratos Inteligentes

- **AcademicIdentity.sol** — Registro descentralizado de identidades acadêmicas
- **CollabProduction.sol** — Regras de produção colaborativa e distribuição de créditos
- **CertificateNFT.sol** — Emissão de certificados como NFTs verificáveis
- **GovernanceDAO.sol** — Organização Autônoma Descentralizada para governança

## 🔐 Conformidade LGPD

O e-VTU implementa mecanismos técnicos para pleno cumprimento da Lei Geral de Proteção de Dados:

- ✅ Minimização de dados na cadeia (apenas hashes)
- ✅ Consentimento explícito via contrato inteligente
- ✅ Crypto-shredding para direito ao esquecimento
- ✅ Portabilidade de dados com assinatura digital
- ✅ Encarregado de Dados (DPO) designado

## 💰 Hospedagem Custo Zero

| Serviço | Custo | Uso |
|---------|-------|-----|
| IPFS via Fleek | Gratuito | Conteúdo estático |
| Vercel Free Tier | Gratuito | Front-end React |
| GitHub Pages | Gratuito | Documentação |
| Web3.Storage | Gratuito até 5GB | Documentos acadêmicos |
| Ethereum Sepolia | Gratuito | Contratos em desenvolvimento |

## 📅 Roadmap

### Fase 0 — Fundação (Meses 1–3)
- Repositório público com documentação técnica
- Contratos inteligentes básicos
- Site institucional

### Fase 1 — MVP (Meses 4–6)
- Portal de cadastro Web3
- Dashboard do estudante
- Módulo de produção colaborativa v1

### Fase 2 — Expansão (Meses 7–12)
- Módulo de mobilidade acadêmica
- Sistema de certificação NFT
- Fórum colaborativo
- Integração com 5 municípios piloto

### Fase 3 — Consolidação (Meses 13–18)
- DAO ativa com governança descentralizada
- Integração com instituições parceiras
- Auditoria de segurança
- Conformidade LGPD certificada

## 🎓 5 Estágios de Produção Colaborativa

1. **Definição do Escopo** — Objetivos, papéis e recursos com apoio de Copiloto IA
2. **Escolha da Plataforma** — Seleção de ferramentas de software livre
3. **Criação da Rede** — Infraestrutura blockchain com templates pré-configurados
4. **Desenvolvimento da DApp** — Colaboração com registro de autoria on-chain
5. **Interface e Lançamento** — Front-end React integrado com publicação descentralizada

## 🌍 Impacto Social Esperado

- 💻 **Inclusão Digital** — Estudantes aprendem blockchain, IA e software livre
- 📍 **Mobilidade Sem Fronteiras** — Participação virtual eliminando custos de deslocamento
- ⚖️ **Governança Democrática** — Decisões transparentes via DAO
- 👑 **Soberania Digital** — Redução de dependência de plataformas comerciais
- 🌿 **Ecossistema Local** — Desenvolvimento de capacidade técnica regional

## 📄 Documentação

- **[Whitepaper Completo](./whitepaper.md)** — Análise técnica e estratégica detalhada
- **[Site Interativo](./index.html)** — Visualizações dinâmicas com gráficos e tabelas

## 🚀 Como Começar

### Clonar o Repositório
```bash
git clone https://github.com/forumacademicors/evtu-web3.git
cd evtu-web3
```

### Executar Localmente
```bash
# Usando Python 3
python3 -m http.server 8000

# Ou usando Node.js (http-server)
npx http-server -p 8000
```

Acesse `http://localhost:8000` no seu navegador.

## 📦 Estrutura do Projeto

```
evtu-web3/
├── index.html              # Site interativo principal
├── whitepaper.md           # Documento técnico completo
├── README.md               # Este arquivo
├── LICENSE                 # Licença MIT
└── assets/                 # (Futuro) Imagens e recursos
```

## 🤝 Contribuindo

O e-VTU é um projeto colaborativo e de código aberto. Contribuições são bem-vindas!

Para contribuir:

1. Faça um fork do repositório
2. Crie uma branch para sua feature (`git checkout -b feature/MinhaFeature`)
3. Commit suas mudanças (`git commit -m 'Adiciona MinhaFeature'`)
4. Push para a branch (`git push origin feature/MinhaFeature`)
5. Abra um Pull Request

## 📞 Contato e Suporte

- **Fórum Acadêmico RS** — Organização estudantil do Rio Grande do Sul
- **Email:** contato@forumacademicors.org
- **GitHub Issues:** Para reportar bugs ou sugerir melhorias

## 📜 Licença

Este projeto está licenciado sob a **MIT License** — veja o arquivo [LICENSE](./LICENSE) para detalhes.

## 🙏 Agradecimentos

- **Fórum Acadêmico RS** — Iniciativa original e visão estratégica
- **Comunidade Ethereum** — Infraestrutura blockchain e ferramentas
- **Comunidade de Software Livre** — Ferramentas e bibliotecas utilizadas
- **Manus AI** — Análise técnica e estruturação do projeto

---

**e-VTU: Educação, Cultura e Tecnologia para Todos**

*Uma iniciativa do Fórum Acadêmico RS para democratizar o acesso ao ensino superior através de tecnologia Web3 descentralizada.*
