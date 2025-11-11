
**INSTITUTO DE DESENVOLVIMENTO SUSTENTÁVEL BAIANO - IDSB**

**TERMO DE FOMENTO Nº 021/2025 – SETRE/FUNTRAD**

---

# PLANO DE DESENVOLVIMENTO DA PLATAFORMA REUNIR
## Trabalho Decente e Produtivo

---

**Responsável Técnico:** Eduardo dos Anjos Pereira
**Função:** Coordenador Técnico de Projeto
**Data:** Novembro de 2025
**Versão:** 1.0

**Municípios Beneficiários:** Vitória da Conquista e Barra do Choça - BA
**Período de Execução:** 12 meses
**Beneficiários Diretos:** 200 pessoas

---

## SUMÁRIO EXECUTIVO

O presente Plano de Desenvolvimento detalha as especificações técnicas, metodológicas e operacionais para implantação da **Plataforma REUNIR: Trabalho Decente e Produtivo**, solução tecnológica destinada à inserção sócio-produtiva de artesãos, pequenos empreendedores e trabalhadores domésticos no Sudoeste Baiano.

A plataforma consistirá em um marketplace digital integrado a um ambiente de aprendizagem, possibilitando comercialização de produtos/serviços online e acesso a conteúdos educativos sobre trabalho decente, prevenção ao trabalho escravo, economia solidária e formalização.

**Investimento Total:** R$ 580.000,00
**Investimento em Tecnologia:** R$ 15.050,00
**Recursos Humanos (Equipe Técnica):** R$ 108.600,00

---

## 1. INTRODUÇÃO

### 1.1 Contextualização

O projeto insere-se nos eixos prioritários II (Erradicação do Trabalho Escravo) e VI (Trabalho Doméstico) da Agenda Bahia do Trabalho Decente, atendendo ao compromisso 004 do PPA 2024-2027: "Disseminar o Trabalho Decente como prevenção à precarização das relações e condições de trabalho".

Nos municípios de Vitória da Conquista e Barra do Choça, dados do Observatório da Erradicação do Trabalho Escravo (1995-2023) registram respectivamente 74 e 41 pessoas resgatadas de condições análogas à escravidão, concentradas majoritariamente no cultivo de café. Adicionalmente, 39,1% e 57,4% dos trabalhadores encontram-se sem carteira assinada, evidenciando vulnerabilidade social e necessidade de alternativas de geração de renda digna.

### 1.2 Objetivo Geral

Desenvolver e implantar plataforma web responsiva, acessível e segura para comercialização de produtos/serviços e disseminação de conteúdos educativos sobre trabalho decente, atendendo 200 beneficiários com vistas à prevenção da precarização laboral e fortalecimento da economia solidária.

### 1.3 Objetivos Específicos Técnicos

1. Implementar marketplace multi-vendor com capacidade para 200 vendedores ativos
2. Desenvolver sistema de gestão de produtos, pedidos e pagamentos integrado
3. Criar ambiente de aprendizagem (LMS) para oficinas e materiais educativos
4. Garantir acessibilidade conforme WCAG 2.1 nível AA
5. Assegurar performance adequada (tempo carregamento < 3s, uptime > 99%)
6. Implementar sistema de analytics para monitoramento de impacto social

### 1.4 Justificativa da Solução Tecnológica

A criação de uma plataforma digital unifica três necessidades identificadas:

a) **Comercialização:** Acesso a mercado consumidor ampliado, sem limitações geográficas
b) **Capacitação:** Centralização de conteúdos educativos acessíveis permanentemente
c) **Articulação:** Fortalecimento de redes de economia solidária e trabalho decente

A tecnologia possibilita alcance escalável, custos operacionais reduzidos e registro sistematizado de impacto social, diferenciando-se de ações pontuais e transitórias.

---

## 2. ESCOPO TÉCNICO DO PROJETO

### 2.1 Funcionalidades Core

#### 2.1.1 Módulo Marketplace

**Para Vendedores (Beneficiários):**
- Cadastro simplificado com dados básicos (CPF, endereço, conta bancária)
- Upload ilimitado de produtos com fotos, descrições e precificação
- Dashboard de vendas com métricas individuais
- Gestão de estoque e disponibilidade
- Sistema de notificações (pedidos, mensagens)
- Histórico de transações

**Para Compradores:**
- Navegação por categorias (Artesanato, Alimentos, Serviços, Outros)
- Busca avançada com múltiplos filtros
- Carrinho de compras e wishlist
- Checkout integrado com múltiplos meios de pagamento
- Rastreamento de pedidos
- Sistema de avaliações e reviews

**Para Administração:**
- Painel de gestão completo (WordPress Admin)
- Aprovação/moderação de vendedores e produtos
- Relatórios de vendas consolidados
- Gestão de comissões e repasses
- Analytics de uso e conversão

#### 2.1.2 Módulo Educativo (LMS)

- Biblioteca digital de materiais (PDFs, vídeos, infográficos)
- Área de oficinas com inscrição e certificação
- Conteúdos estruturados por temática:
  - Cidadania e Direitos Humanos
  - Trabalho Decente e Legislação
  - Prevenção ao Trabalho Escravo
  - Formalização (MEI) e Proteção Social
  - Economia Solidária e Associativismo
  - Precificação e Gestão Financeira
  - Marketing e Vendas Online
- Sistema de progressão e certificados digitais

#### 2.1.3 Módulo Institucional

- Páginas informativas sobre o projeto e Agenda Bahia
- Área de notícias e eventos
- Formulários de contato e suporte
- FAQ (Perguntas Frequentes)
- Política de Privacidade e Termos de Uso (LGPD)

### 2.2 Requisitos Não-Funcionais

| **Categoria** | **Requisito** | **Especificação** |
|---|---|---|
| **Performance** | Tempo de carregamento | Primeira página < 3s; demais < 2s |
| | Capacidade | 500 usuários simultâneos |
| | Otimização imagens | Compressão automática, lazy loading |
| **Segurança** | Certificação | SSL/HTTPS obrigatório |
| | Backup | Diário (banco) + semanal (completo) |
| | Proteção | Firewall, anti-malware, 2FA admin |
| | LGPD | Conformidade total (consentimento, portabilidade) |
| **Acessibilidade** | Padrão | WCAG 2.1 nível AA |
| | Navegação | Teclado, leitores de tela compatíveis |
| | Contraste | Textos legíveis, botões identificáveis |
| **Disponibilidade** | Uptime | Mínimo 99% (SLA hospedagem) |
| | Monitoramento | 24/7 com alertas automáticos |
| **Responsividade** | Dispositivos | Desktop, tablet, smartphone |
| | Navegadores | Chrome, Firefox, Safari, Edge (2 últimas versões) |

---

## 3. ARQUITETURA E TECNOLOGIAS

### 3.1 Stack Tecnológica Selecionada

**Plataforma Base:** WordPress 6.x + WooCommerce 8.x

**Justificativa:**
- Gratuito e open-source (redução de custos)
- Curva de aprendizado suave (equipe e beneficiários)
- Ecosistema robusto de plugins especializados
- Suporte nativo a e-commerce e LMS
- Comunidade ativa com documentação em português
- Escalabilidade comprovada (milhões de sites globalmente)

**Alternativas Consideradas e Descartadas:**
- **Shopify:** Custo recorrente elevado, menor flexibilização
- **Magento:** Complexidade técnica incompatível com equipe disponível
- **Desenvolvimento Custom:** Prazo e custo inviáveis dentro do escopo

### 3.2 Infraestrutura de Hospedagem

| **Componente** | **Provedor/Tecnologia** | **Especificação** | **Custo Anual** |
|---|---|---|---|
| **Hospedagem Web** | [A DEFINIR: SiteGround / Hostinger] | 4 vCPU, 8GB RAM, 100GB SSD | R$ 4.200,00 |
| **Domínio** | Registro.br | .com.br | R$ 200,00 |
| **CDN** | Cloudflare | Plan Pro | R$ 2.400,00 |
| **Storage Adicional** | Amazon S3 | 100GB inicial | R$ 2.400,00 |
| **Backup Premium** | UpdraftPlus | Licença anual | R$ 250,00 |
| **Segurança** | Wordfence Premium | Licença anual | R$ 400,00 |
| **TOTAL** | | | **R$ 9.850,00** |

**Ambientes:**
- **Desenvolvimento:** Local (equipe técnica)
- **Homologação:** Subdomínio staging.plataformareunir.com.br
- **Produção:** www.plataformareunir.com.br

### 3.3 Plugins e Extensões

| **Funcionalidade** | **Plugin** | **Licença** | **Custo Anual** |
|---|---|---|---|
| **Marketplace Multi-Vendor** | Dokan Pro | Premium | R$ 1.200,00 |
| **LMS (Educação)** | LearnDash | Premium | R$ 800,00 |
| **SEO** | Yoast SEO Premium | Premium | R$ 400,00 |
| **Cache/Performance** | WP Rocket | Premium | R$ 450,00 |
| **Analytics** | MonsterInsights Pro | Premium | R$ 350,00 |
| **Formulários** | Gravity Forms | Premium | R$ 350,00 |
| **Backup** | UpdraftPlus Premium | Premium | R$ 250,00 |
| **Segurança** | Wordfence Premium | Premium | R$ 400,00 |
| **E-mail Marketing** | Mailchimp for WooCommerce | Gratuito | R$ 0,00 |
| **Compressor Imagens** | ShortPixel | Premium | R$ 300,00 |
| **LGPD/Cookie** | CookieYes | Premium | R$ 300,00 |
| **TOTAL PLUGINS** | | | **R$ 4.800,00** |

**Tema Premium:** Flatsome ou Astra Pro (R$ 400,00 - investimento único)

### 3.4 Integrações Essenciais

#### 3.4.1 Gateway de Pagamento
**Opção Principal:** Mercado Pago
**Métodos:** Cartão crédito/débito, Boleto, PIX
**Taxa Plataforma:** A definir (sugestão: 3-5% por transação)

**Alternativas:** PagSeguro, Stripe (internacional)

#### 3.4.2 Logística
- Integração Correios via plugin Melhor Envio
- Opção de retirada local (acordado diretamente)
- Frete grátis configurável (ex: compras > R$ 100)

#### 3.4.3 Comunicação
- SMTP via SendGrid ou Mailgun (e-mails transacionais)
- WhatsApp Business API (notificações - futuro)

---

## 4. METODOLOGIA DE DESENVOLVIMENTO

### 4.1 Abordagem Ágil Adaptada

**Framework:** Scrum simplificado (equipe pequena)

**Sprints:** 2 semanas (6 sprints totais no desenvolvimento)

**Papéis:**
- **Product Owner:** Eduardo dos Anjos Pereira (Coordenador Técnico)
- **Scrum Master:** Camillo Alves Marcarenhas (Gestor de Desenvolvimento)
- **Dev Team:** Rodrigo Pena (UX/UI), Thyerry Pires (Suporte/QA)
- **Stakeholders:** Antonio Eduardo (Coord. Geral), Vanêssa Pontes (Comunicação)

**Cerimônias:**
- **Sprint Planning:** Segunda-feira, início de sprint (2h)
- **Daily Stand-up:** Semanal (equipe remota) - 30min
- **Sprint Review:** Sexta-feira, fim de sprint (1h) - apresentação para stakeholders
- **Retrospectiva:** Interna, melhorias processuais (30min)

**Ferramentas:**
- **Gestão:** Trello ou Asana (kanban board)
- **Comunicação:** WhatsApp (grupo equipe) + Google Meet (reuniões formais)
- **Documentação:** Google Drive (compartilhado)
- **Versionamento:** Git + GitHub (código customizado)

### 4.2 Fases e Cronograma Macro

| **Fase** | **Período** | **Duração** | **Entregas Principais** |
|---|---|---|---|
| **1. Planejamento** | Mês 4 | 4 semanas | Requisitos, wireframes, stack definida |
| **2. Design** | Mês 5 | 4 semanas | Mockups, protótipo, guia de estilo |
| **3. Desenvolvimento Core** | Meses 6-7 | 8 semanas | Marketplace funcional, páginas base |
| **4. Conteúdo Educativo** | Mês 8 | 4 semanas | LMS implementado, materiais carregados |
| **5. Testes** | Meses 9-10 | 8 semanas | Testes completos, correções, otimizações |
| **6. Lançamento** | Mês 11 | 4 semanas | Go-live, eventos, treinamentos |
| **7. Manutenção** | Mês 12 | 4 semanas | Suporte, ajustes, documentação final |

---

## 5. DESENVOLVIMENTO DETALHADO

### 5.1 FASE 1 - Planejamento e Preparação (Mês 4)

**Objetivos:**
- Consolidar requisitos com equipe multidisciplinar
- Definir identidade visual e wireframes
- Contratar serviços de infraestrutura
- Configurar ambientes de desenvolvimento

**Atividades:**

**Semana 1:**
- Reunião de kickoff com toda equipe (2h)
- Levantamento de requisitos detalhados (2 reuniões de 2h cada)
- Definição de categorias de produtos
- Mapeamento de perfis de usuários (personas)

**Semana 2:**
- Contratação de hospedagem e registro de domínio
- Instalação WordPress em ambiente de desenvolvimento
- Criação de wireframes principais (Rodrigo - UX/UI):
  - Homepage
  - Listagem de produtos
  - Página de produto
  - Dashboard vendedor
  - Checkout
- Workshop de identidade visual (2h com Vanêssa)

**Semana 3:**
- Definição de paleta de cores e tipografia
- Configuração de ambientes (dev, staging, produção)
- Instalação de plugins essenciais (teste)
- Criação de estrutura de navegação (sitemap)

**Semana 4:**
- Aprovação de wireframes com stakeholders
- Planejamento de sprints do desenvolvimento
- Definição de critérios de aceitação para funcionalidades
- Preparação para fase de design

**Entregas:**
- ✅ Documento de Requisitos Funcionais
- ✅ Wireframes aprovados (Figma)
- ✅ Stack tecnológica contratada e configurada
- ✅ Cronograma detalhado de sprints

---

### 5.2 FASE 2 - Design e Prototipagem (Mês 5)

**Objetivos:**
- Criar mockups high-fidelity de todas as páginas principais
- Desenvolver protótipo interativo para testes
- Validar usabilidade com amostra de beneficiários
- Produzir guia de estilo (design system)

**Atividades:**

**Semana 1-2:**
- Criação de mockups detalhados (Rodrigo):
  - Todas as páginas do wireframe
  - Versões desktop, tablet e mobile
  - Estados (normal, hover, ativo, erro)
- Definição de componentes reutilizáveis (botões, cards, formulários)
- Criação de ícones e ilustrações customizadas

**Semana 3:**
- Montagem de protótipo interativo no Figma
- Testes de usabilidade com 10-15 beneficiários (presencial):
  - Tarefas: buscar produto, adicionar ao carrinho, cadastrar-se como vendedor
  - Coleta de feedback qualitativo
  - Identificação de pontos de fricção
- Análise de resultados (métricas: taxa de sucesso, tempo, erros)

**Semana 4:**
- Ajustes de design baseados em feedback
- Aprovação final com coordenação geral
- Produção de Guia de Estilo:
  - Paleta de cores (códigos hex)
  - Tipografia (famílias, tamanhos, pesos)
  - Espaçamentos e grid
  - Componentes (botões, formulários, cards)
  - Ícones e imagens
- Handoff para desenvolvimento (exportação de assets)

**Entregas:**
- ✅ Mockups finalizados (Figma - todas as telas)
- ✅ Protótipo interativo
- ✅ Relatório de Testes de Usabilidade
- ✅ Guia de Estilo (PDF)
- ✅ Assets exportados (ícones, imagens)

---

### 5.3 FASE 3 - Desenvolvimento Core (Meses 6-7)

**Objetivos:**
- Implementar marketplace funcional
- Configurar sistema de pagamentos
- Desenvolver páginas estáticas
- Preparar versão beta para testes internos

**Sprint 1 (Semanas 1-2 / Mês 6):**

**Tarefas:**
- Instalação e configuração WordPress + WooCommerce em staging
- Instalação e ativação de tema premium (Flatsome/Astra)
- Customização de tema conforme mockups (CSS personalizado)
- Instalação de plugins core (Dokan, Yoast SEO, WP Rocket)
- Configuração básica WooCommerce:
  - Moeda (BRL)
  - País/região (Brasil - Bahia)
  - Configuração de taxas (se aplicável)
  - Métodos de envio inicial

**Sprint 2 (Semanas 3-4 / Mês 6):**

**Tarefas:**
- Configuração completa Dokan Marketplace:
  - Tipos de usuário (vendedor, comprador, admin)
  - Processo de aprovação de vendedores (manual)
  - Configuração de comissões (% a definir)
  - Dashboard do vendedor personalizado
- Criação de categorias de produtos:
  - Artesanato
  - Alimentos
  - Serviços
  - Outros
- Implementação de formulário de cadastro vendedor (Gravity Forms)
- Desenvolvimento de páginas estáticas:
  - Sobre o Projeto
  - Como Vender
  - Como Comprar
  - FAQ

**Sprint 3 (Semanas 1-2 / Mês 7):**

**Tarefas:**
- Integração com gateway de pagamento (Mercado Pago):
  - Configuração de credenciais
  - Testes em ambiente sandbox
  - Ativação de métodos (cartão, boleto, PIX)
- Configuração de e-mails transacionais:
  - Templates personalizados (novo pedido, confirmação, etc.)
  - Configuração SMTP
- Implementação de sistema de avaliações e reviews
- Configuração de SEO básico (Yoast):
  - Meta descriptions
  - Títulos
  - Sitemap XML

**Sprint 4 (Semanas 3-4 / Mês 7):**

**Tarefas:**
- Desenvolvimento de homepage customizada (Elementor/Visual Builder)
- Implementação de busca avançada com filtros
- Configuração de analytics (Google Analytics 4):
  - Eventos personalizados (cadastro vendedor, compra, etc.)
  - Metas de conversão
- Otimização de performance:
  - Configuração de cache (WP Rocket)
  - Compressão de imagens (ShortPixel)
  - Lazy loading
- Testes internos de fluxo completo (equipe)

**Entregas Fase 3:**
- ✅ Marketplace funcional em staging
- ✅ Sistema de pagamento integrado e testado
- ✅ Páginas estáticas publicadas
- ✅ Analytics configurado
- ✅ Versão beta operacional

---

### 5.4 FASE 4 - Conteúdo Educativo (Mês 8)

**Objetivos:**
- Implementar LMS (Learning Management System)
- Estruturar biblioteca de conteúdos
- Carregar materiais das oficinas
- Criar área de certificação

**Atividades:**

**Semana 1:**
- Instalação e configuração LearnDash (plugin LMS)
- Criação de estrutura de cursos/oficinas:
  - Curso 1: Cidadania e Direitos Humanos (4h)
  - Curso 2: Trabalho Decente (4h)
  - Curso 3: Direitos e Trabalho Escravo (4h)
  - Curso 4: Formalização e Proteção Social (8h)
  - Curso 5: Economia Solidária e Associativismo (8h)
  - Curso 6: Precificação (8h)
  - Curso 7: Uso de Tecnologia para Vendas (8h)
- Definição de pré-requisitos e sequenciamento

**Semana 2:**
- Upload de materiais educativos:
  - PDFs (apresentações das oficinas)
  - Vídeos (gravações ou links YouTube)
  - Infográficos
  - Artigos e textos de apoio
- Criação de páginas de descrição de cada curso
- Configuração de sistema de inscrição

**Semana 3:**
- Desenvolvimento de biblioteca digital organizada por tema:
  - Legislação trabalhista
  - Formalização (passo a passo MEI)
  - Precificação (planilhas e ferramentas)
  - Marketing digital básico
- Implementação de sistema de busca de conteúdos
- Criação de página "Aprenda" (hub central)

**Semana 4:**
- Configuração de certificados digitais (LearnDash)
- Criação de quizzes de avaliação (opcionais)
- Testes de acesso e navegação
- Ajustes de layout e UX

**Entregas:**
- ✅ LMS completo e funcional
- ✅ 7 cursos/oficinas estruturados
- ✅ Biblioteca digital com mínimo 30 materiais
- ✅ Sistema de certificação ativo

---

### 5.5 FASE 5 - Testes e Ajustes (Meses 9-10)

**Objetivos:**
- Executar bateria completa de testes (funcional, performance, segurança, acessibilidade)
- Corrigir bugs identificados
- Otimizar performance
- Validar com grupo piloto de beneficiários

**Mês 9:**

**Semana 1: Testes Funcionais**
- Checklist completo de funcionalidades:
  - Cadastro/login de usuários (todos os perfis)
  - CRUD produtos (vendedor)
  - Processo de compra completo (do carrinho ao pagamento)
  - Notificações por e-mail (todas as triggers)
  - Dashboard vendedor (todas as seções)
  - Moderação admin (aprovações, relatórios)
  - Acesso e progressão em cursos (LMS)
- Documentação de bugs encontrados (Trello - priorização)

**Semana 2: Testes de Performance**
- Análise com ferramentas:
  - Google PageSpeed Insights
  - GTmetrix
  - Pingdom
- Métricas alvo:
  - Homepage: < 3s
  - Página produto: < 2s
  - Checkout: < 2.5s
  - LCP (Largest Contentful Paint): < 2.5s
  - FID (First Input Delay): < 100ms
  - CLS (Cumulative Layout Shift): < 0.1
- Teste de carga (simulação 100, 300, 500 usuários simultâneos)
- Implementação de otimizações identificadas

**Semana 3: Testes de Segurança**
- Scan completo com Wordfence
- Verificação de certificado SSL
- Teste de formulários (SQL injection, XSS)
- Revisão de permissões de usuários
- Teste de backup e restauração (simulação)
- Implementação de medidas corretivas

**Semana 4: Testes de Acessibilidade**
- Auditoria com ferramentas:
  - WAVE (Web Accessibility Evaluation Tool)
  - axe DevTools
  - Lighthouse (Acessibilidade)
- Checklist WCAG 2.1 Nível AA:
  - Contraste de cores (mínimo 4.5:1)
  - Navegação por teclado (tab order)
  - Alt text em imagens
  - Labels em formulários
  - Estrutura HTML semântica (H1, H2, etc.)
  - Compatibilidade com leitores de tela (NVDA/JAWS)
- Correções identificadas

**Mês 10:**

**Semana 1-2: Grupo Piloto**
- Seleção de 20-30 beneficiários (mix: vendedores e compradores)
- Convite e orientação inicial (presencial - 2h)
- Período de uso livre (10 dias):
  - Vendedores: cadastrar perfil e mínimo 3 produtos
  - Compradores: navegar, adicionar ao carrinho, simular compra
- Suporte dedicado via WhatsApp
- Coleta de feedback:
  - Questionário estruturado (SUS - System Usability Scale)
  - Entrevistas qualitativas (5-10 participantes)
  - Registro de dificuldades e sugestões

**Semana 3: Análise e Ajustes**
- Consolidação de feedback do piloto
- Priorização de ajustes (crítico → cosmético)
- Implementação de melhorias identificadas
- Re-teste de funcionalidades alteradas

**Semana 4: Testes de Regressão**
- Repetição de testes funcionais core após ajustes
- Verificação de não introdução de novos bugs
- Performance final (última otimização)
- Preparação para go-live

**Entregas:**
- ✅ Relatório de Testes Completo (funcional, performance, segurança, acessibilidade)
- ✅ Lista de bugs corrigidos (changelog)
- ✅ Relatório de Piloto com Beneficiários
- ✅ Plataforma validada e pronta para produção

---

### 5.6 FASE 6 - Lançamento (Mês 11)

**Objetivos:**
- Migrar plataforma para ambiente de produção
- Realizar eventos de lançamento nos municípios
- Cadastrar primeiros vendedores oficiais
- Iniciar campanha de marketing digital

**Semana 1: Migração e Go-Live**
- Backup completo de staging
- Migração de banco de dados para produção
- Configuração de DNS (apontamento domínio)
- Verificação de certificado SSL em produção
- Configuração final de gateway de pagamento (credenciais reais)
- Smoke test (teste rápido de funcionalidades críticas)
- Monitoramento intensivo (primeiras 48h)

**Semana 2: Evento de Lançamento - Vitória da Conquista**
- Evento presencial (conforme Ação 5 - Plano de Trabalho)
- Apresentação da plataforma (demo ao vivo)
- Cadastro de primeiros vendedores
- Sessão de dúvidas e treinamento prático (2-3h)
- Coleta de feedback inicial
- Material de apoio (passo a passo impresso + vídeos tutoriais)

**Semana 3: Evento de Lançamento - Barra do Choça**
- Repetição do evento no segundo município
- Adaptação baseada em lições do primeiro evento
- Cadastramento de vendedores locais

**Semana 4: Campanha de Marketing Digital**
- Ativação de campanhas (coordenação com Vanêssa):
  - Google Ads (palavras-chave locais)
  - Facebook/Instagram Ads (segmentação geográfica)
  - Impulsionamento de posts
- Produção de conteúdo:
  - Posts redes sociais (diário)
  - Stories (bastidores, produtos em destaque)
  - E-mail marketing (newsletter de lançamento)
- Parcerias com influenciadores locais (microinfluenciadores)
- Divulgação em rádios e jornais locais

**Entregas:**
- ✅ Plataforma no ar em produção (www.plataformareunir.com.br)
- ✅ 2 eventos de lançamento realizados
- ✅ Mínimo 50 vendedores cadastrados
- ✅ Primeiras transações registradas
- ✅ Campanha de marketing ativa

---

### 5.7 FASE 7 - Manutenção e Documentação (Mês 12)

**Objetivos:**
- Fornecer suporte contínuo aos usuários
- Monitorar métricas e corrigir problemas emergenciais
- Coletar dados de impacto social
- **Produzir Relatório Final de Implantação (ENTREGA OBRIGATÓRIA)**

**Semana 1-2: Operação e Suporte**
- Suporte dedicado via WhatsApp/e-mail (Thyerry)
- Monitoramento de analytics (Eduardo):
  - Visitantes diários
  - Taxa de conversão
  - Produtos mais vistos
  - Vendedores mais ativos
- Correções de bugs emergenciais
- Atualizações de segurança (WordPress, plugins)

**Semana 3: Coleta de Dados de Impacto**
- Questionário aos vendedores:
  - Aumento de vendas/renda (comparativo)
  - Satisfação com a plataforma (NPS)
  - Dificuldades enfrentadas
  - Sugestões de melhoria
- Extração de métricas da plataforma:
  - Total de vendedores ativos
  - Total de produtos publicados
  - Número de pedidos
  - Valor total transacionado
  - Acesso a conteúdos educativos (views, conclusões)
- Cruzamento com dados sociodemográficos (perfil beneficiários)

**Semana 4: Documentação Final**
- **Elaboração do Relatório de Implantação da Plataforma:**
  - Sumário executivo
  - Descrição técnica da solução implementada
  - Tecnologias utilizadas (detalhamento)
  - Processo de desenvolvimento (fases, desafios, soluções)
  - Resultados alcançados (métricas)
  - Avaliação de impacto social (preliminar)
  - Lições aprendidas
  - Recomendações para sustentabilidade
  - Anexos (prints, diagramas, dados)
- Documentação técnica para equipe futura:
  - Manual do administrador
  - Guia de troubleshooting
  - Contatos de suporte (hospedagem, plugins)
  - Credenciais e acessos (documento protegido)
- Vídeos tutoriais finais (vendedores e compradores)

**Entregas:**
- ✅ Plataforma estável e operacional
- ✅ Base de usuários consolidada (200 vendedores meta)
- ✅ Dados de impacto coletados
- ✅ **RELATÓRIO DE IMPLANTAÇÃO DA PLATAFORMA (documento oficial)**
- ✅ Documentação técnica completa
- ✅ Materiais de treinamento atualizados

---

## 6. SEGURANÇA, BACKUP E LGPD

### 6.1 Estratégia de Segurança

**Camadas de Proteção:**

1. **Nível Infraestrutura:**
   - Firewall de rede (hospedagem)
   - Certificado SSL/TLS (HTTPS obrigatório)
   - Proteção DDoS (Cloudflare)

2. **Nível Aplicação:**
   - Wordfence Premium (firewall WordPress)
   - Bloqueio de IPs suspeitos
   - Limitação de tentativas de login (5 tentativas → bloqueio 30min)
   - Autenticação de dois fatores (2FA) para administradores

3. **Nível Dados:**
   - Senhas criptografadas (hash bcrypt)
   - Dados bancários não armazenados (tokenização via gateway)
   - Backups criptografados

**Política de Senhas:**
- Mínimo 12 caracteres
- Combinação obrigatória: maiúsculas, minúsculas, números, símbolos
- Expiração semestral (administradores)
- Proibição de senhas comuns (dictionary attack prevention)

**Atualizações:**
- **Críticas:** Imediatas (< 24h após release)
- **Segurança:** Semanais
- **Funcionais:** Mensais (após teste em staging)

**Monitoramento:**
- Uptime Robot (ping a cada 5min, alertas por e-mail)
- Wordfence scan diário (malware, vulnerabilidades)
- Logs de acesso revisados semanalmente

### 6.2 Política de Backup

**Frequência:**
| **Tipo** | **Conteúdo** | **Frequência** | **Retenção** |
|---|---|---|---|
| Incremental | Banco de dados | Diário (3h da manhã) | 7 dias |
| Completo | Arquivos + BD | Semanal (domingo 2h) | 4 semanas |
| Full Archive | Tudo | Mensal (dia 1, 2h) | 6 meses |

**Localização (Regra 3-2-1):**
- **Servidor:** Pasta protegida na hospedagem (cópia 1)
- **Amazon S3:** Upload automático via UpdraftPlus (cópia 2 - nuvem)
- **Download Local:** Backup mensal baixado e armazenado em HD externo (cópia 3 - offline)

**Testes de Restauração:**
- Trimestral: Restaurar backup completo em ambiente de teste
- Documentar tempo de recuperação (RTO - Recovery Time Objective: meta < 4h)

### 6.3 Conformidade LGPD

**Dados Pessoais Coletados:**

| **Categoria** | **Dados** | **Finalidade** | **Base Legal** |
|---|---|---|---|
| Compradores | Nome, e-mail, telefone, endereço, CPF | Processamento de pedidos | Execução de contrato |
| Vendedores | Dados acima + RG, dados bancários, fotos | Cadastro e repasses financeiros | Execução de contrato |
| Navegação | IP, cookies, páginas visitadas | Analytics, melhorias | Legítimo interesse |

**Medidas de Conformidade:**

- ✅ Política de Privacidade publicada e acessível (footer)
- ✅ Termos de Uso aceitos no cadastro (checkbox obrigatório)
- ✅ Banner de cookies (CookieYes) com opção de aceitar/rejeitar
- ✅ Consentimento explícito para coleta de dados sensíveis
- ✅ Funcionalidade "Exportar meus dados" (JSON ou PDF)
- ✅ Funcionalidade "Excluir minha conta" (GDPR/LGPD compliant)
- ✅ Criptografia de dados sensíveis em repouso
- ✅ Anonimização em relatórios agregados

**Direitos dos Titulares:**
- Acesso: Usuário pode visualizar dados no painel
- Correção: Usuário pode editar informações
- Exclusão: Solicitação via formulário → exclusão em até 7 dias
- Portabilidade: Download de dados em formato estruturado
- Revogação: Usuário pode desativar conta a qualquer momento

**Encarregado (DPO):** [A DEFINIR - pode ser o Coordenador Administrativo Wilde]

---

## 7. INDICADORES E AVALIAÇÃO

### 7.1 Indicadores Técnicos

| **Indicador** | **Meta** | **Fonte** | **Frequência Medição** |
|---|---|---|---|
| Disponibilidade (Uptime) | ≥ 99% | UptimeRobot | Contínua |
| Tempo carregamento médio | < 3s | Google Analytics | Semanal |
| Core Web Vitals "Bom" | 100% páginas | PageSpeed Insights | Mensal |
| Erros críticos | 0/mês | Logs + Wordfence | Diário |
| Vulnerabilidades | 0 detectadas | Wordfence scan | Diário |
| Sucesso backups | 100% | UpdraftPlus logs | Diário |

### 7.2 Indicadores de Uso

| **Indicador** | **Meta Ano 1** | **Fonte** | **Frequência** |
|---|---|---|---|
| Vendedores cadastrados | 200 | WordPress (usuários com perfil "vendedor") | Mensal |
| Vendedores ativos (≥1 produto) | 150 (75%) | Dokan reports | Mensal |
| Produtos publicados | 800 (média 4/vendedor) | WooCommerce | Mensal |
| Visitantes únicos/mês | 5.000 | Google Analytics | Mensal |
| Pedidos/mês | 100 (crescente) | WooCommerce | Mensal |
| Valor total vendido (acumulado ano) | R$ 60.000 | WooCommerce | Mensal |
| Taxa de conversão (visita→compra) | ≥ 2% | Analytics + WooCommerce | Mensal |
| Acessos a conteúdo educativo | 2.000 | LearnDash analytics | Mensal |
| Cursos concluídos | 100 | LearnDash | Trimestral |

### 7.3 Indicadores de Impacto Social (Alinhados ao Plano de Trabalho)

| **Indicador** | **Meta** | **Fonte** | **Frequência** |
|---|---|---|---|
| Aumento de renda vendedores | ≥ 20% (autodeclarado) | Questionário pré/pós | Semestral |
| Vendedores formalizados (MEI) | ≥ 50% | Questionário | Semestral |
| Satisfação vendedores (NPS) | ≥ 8/10 | Pesquisa NPS | Trimestral |
| Participação de mulheres | ≥ 70% | Cadastros (campo gênero) | Mensal |
| Participação de pessoas negras | ≥ 70% | Cadastros (autodeclaração opcional) | Mensal |
| Beneficiários capacitados (oficinas) | 200 | Listas de presença (Ação 5) | Conforme oficinas |

### 7.4 Dashboards e Relatórios

**Dashboard Técnico (Eduardo - Coordenador Técnico):**
- Google Analytics (tempo real + métricas semanais)
- WooCommerce Reports (vendas, produtos, vendedores)
- UptimeRobot (disponibilidade)
- Wordfence (segurança)

**Relatórios Gerenciais (Antonio - Coordenador Geral):**
- Mensal: Consolidado de métricas principais (1 página)
- Trimestral: Análise aprofundada + recomendações (3-5 páginas)
- Semestral: Pesquisa de satisfação + avaliação de impacto

**Ferramentas:**
- Google Data Studio (dashboards visuais automáticos)
- MonsterInsights (WordPress plugin - relatórios no admin)
- Planilhas Google (consolidação manual de dados sociais)

---

## 8. SUSTENTABILIDADE E CONTINUIDADE

### 8.1 Custos Operacionais Pós-Projeto (Anual)

| **Item** | **Custo Anual** | **Observações** |
|---|---|---|
| Hospedagem | R$ 4.200,00 | Pode renegociar após ano 1 |
| Domínio | R$ 200,00 | Renovação anual .com.br |
| Plugins Premium | R$ 4.800,00 | Renovação de licenças |
| CDN | R$ 2.400,00 | Cloudflare Pro |
| Storage/Backup | R$ 2.400,00 | Amazon S3 + UpdraftPlus |
| Segurança | R$ 400,00 | Wordfence Premium |
| **TOTAL INFRAESTRUTURA** | **R$ 14.400,00** | **R$ 1.200/mês** |
| | | |
| Suporte Técnico (freelancer) | R$ 18.000,00 | R$ 1.500/mês (20h) - opcional |
| Marketing Digital | R$ 12.000,00 | R$ 1.000/mês (ads + conteúdo) - variável |
| **TOTAL COM OPERAÇÃO** | **R$ 44.400,00** | **R$ 3.700/mês** |

**Observação:** Custos operacionais básicos (infraestrutura) são viáveis dentro da receita de comissões projetada. Operação completa (com equipe) requer planejamento de sustentabilidade adicional.

### 8.2 Modelo de Receita

**Fonte Principal: Comissão sobre Vendas**

**Proposta Inicial:** 5% sobre cada transação

**Projeção Conservadora:**
- 150 vendedores ativos (75% dos 200)
- Vendas médias: R$ 400/vendedor/mês
- Faturamento total plataforma: R$ 60.000/mês
- Comissão (5%): **R$ 3.000/mês** = **R$ 36.000/ano**

**Projeção Otimista:**
- 200 vendedores ativos
- Vendas médias: R$ 600/vendedor/mês
- Faturamento total: R$ 120.000/mês
- Comissão (5%): **R$ 6.000/mês** = **R$ 72.000/ano**

**Análise:**
- Cenário conservador cobre custos de infraestrutura (R$ 14.400) com margem
- Cenário otimista permite reinvestimento em melhorias e expansão
- Necessário buscar fontes complementares para equipe permanente

**Outras Fontes (Futuras - Pós Ano 1):**
- Planos premium para vendedores (destaque, mais produtos, analytics): R$ 30-50/mês
- Publicidade (banners, produtos patrocinados): variável
- Cursos pagos avançados: R$ 50-100/curso
- Parcerias com empresas (programa de fornecedores): comissão diferenciada

### 8.3 Estratégia de Transição (Final do Termo de Fomento)

**Mês 12 - Ações Prioritárias:**

1. **Avaliação de Viabilidade Financeira:**
   - Análise receita vs despesas (projeção 12 meses)
   - Identificação de gargalos e oportunidades
   - Definição de modelo de governança permanente

2. **Busca de Financiamento Complementar:**
   - Novos editais (SETRE, outros órgãos)
   - Parcerias com Prefeituras (convênios)
   - Programas de ESG empresas privadas (responsabilidade social)
   - Doações via IDSB (transparência Lei Rouanet/similares)

3. **Capacitação Equipe de Transição:**
   - Treinamento técnico completo (administração plataforma)
   - Transferência de conhecimento (documentação detalhada)
   - Definição de equipe mínima (1 técnico + 1 suporte)
   - Contratação de freelancers para demandas específicas

4. **Governança Participativa:**
   - Criação de conselho consultivo (IDSB + representantes vendedores)
   - Reuniões trimestrais para decisões estratégicas
   - Participação de beneficiários na gestão (empoderamento)

### 8.4 Roadmap Pós-Implantação

**Curto Prazo (6 meses após lançamento):**
- Ajustes finos baseados em uso real
- Expansão gradual de vendedores (300-400)
- Desenvolvimento de app mobile (PWA - Progressive Web App)
- Integração com redes sociais (venda via Instagram Shopping)

**Médio Prazo (12-18 meses):**
- Expansão para outros municípios do Sudoeste Baiano
- Parcerias com cooperativas e associações
- Implementação de marketplace B2B (vendedores → lojistas)
- Gamificação (badges, níveis, recompensas para engajamento)

**Longo Prazo (24 meses+):**
- Replicação do modelo em outros territórios da Bahia
- Franquia social (licenciamento para outras OSCs)
- Plataforma white-label para outras redes de economia solidária
- Internacionalização (países lusófonos - Angola, Moçambique)

---

## 9. RISCOS E MITIGAÇÃO

### 9.1 Matriz de Riscos

| **Risco** | **Prob.** | **Impacto** | **Mitigação** | **Contingência** |
|---|---|---|---|---|
| Atraso cronograma | Média | Alto | Sprints com buffer; priorização rigorosa | Reduzir escopo não-essencial; extensão prazo negociada |
| Baixa adesão vendedores | Alta | Crítico | Mobilização intensiva (Vinícius); UX simplificado; suporte dedicado | Revisão de estratégia; incentivos (isenção comissão inicial); gamificação |
| Problemas técnicos no lançamento | Baixa | Alto | Testes extensivos (Fase 5); piloto prévio; checklist go-live | Rollback imediato; página manutenção; comunicação transparente |
| Ataque cibernético | Baixa | Crítico | Segurança em camadas; backups diários; monitoramento 24/7 | Plano de resposta a incidentes; restauração de backup; comunicação LGPD |
| Dificuldade vendedores com tecnologia | Alta | Alto | Oficinas práticas (Ação 5); materiais visuais; suporte WhatsApp | Treinamentos extras; vídeos tutoriais; atendimento presencial pontual |
| Baixo engajamento compradores | Alta | Alto | Marketing digital agressivo (Vanêssa); SEO; parcerias locais; eventos | Revisão de estratégia de comunicação; promoções; programa de fidelidade |
| Incompatibilidade plugins | Média | Médio | Testes em staging; plugins bem avaliados; updates controlados | Downgrade versão; busca de plugin alternativo; desenvolvimento custom |
| Orçamento insuficiente | Baixa | Alto | Controle rigoroso (Wilde); priorização gastos; renegociação fornecedores | Redução de escopo; busca de alternativas gratuitas; apoio IDSB |

### 9.2 Plano de Contingência - Cenários Críticos

**Cenário 1: Downtime Prolongado (>4h)**

**Ações Imediatas:**
1. Notificar Coordenação Geral e SETRE (1h após incidente)
2. Ativar página de manutenção com previsão de retorno
3. Comunicar vendedores via WhatsApp (grupo broadcast)
4. Diagnosticar causa (logs servidor + hospedagem)
5. Restaurar de backup se necessário
6. Testar funcionalidades críticas antes de reativar
7. Pós-análise: documentar causa e ações preventivas

**Cenário 2: Violação de Dados (LGPD)**

**Ações Imediatas:**
1. Isolar sistema comprometido (offline imediato)
2. Investigar extensão da violação (que dados, quantos usuários)
3. Notificar ANPD em até 72h (obrigação legal)
4. Comunicar afetados em até 5 dias (e-mail oficial)
5. Oferecer medidas de mitigação (troca senhas, monitoramento CPF)
6. Contratar auditoria de segurança externa
7. Implementar recomendações e fortalecer proteções

**Cenário 3: Falha no Gateway de Pagamento**

**Ações Imediatas:**
1. Desativar checkout temporariamente
2. Contatar suporte do gateway (prioridade máxima)
3. Comunicar aos vendedores (pedidos pendentes)
4. Ativar método alternativo se disponível (ex: PagSeguro como backup)
5. Processar pedidos offline excepcionalmente (via transferência direta)
6. Resolver falha e reativar + comunicado
7. Compensar vendedores por pedidos perdidos (se aplicável)

---

## 10. EQUIPE E RESPONSABILIDADES

### 10.1 Estrutura da Equipe Técnica

| **Função** | **Nome** | **Atribuições Principais** | **Dedicação** | **Remuneração Mensal** |
|---|---|---|---|---|
| **Coordenador Técnico** | Eduardo dos Anjos Pereira | Liderança técnica, planejamento, relatórios, coordenação equipe | 30h/semana | R$ 2.700,00 |
| **Gestor de Desenvolvimento** | Camillo Alves Marcarenhas | Gestão de produto, cronograma, comunicação stakeholders | 30h/semana | R$ 2.700,00 |
| **Designer UX/UI** | Rodrigo Pena | Wireframes, mockups, testes usabilidade, guia de estilo | 30h/semana | R$ 2.300,00 |
| **Técnico de Suporte** | Thyerry Pires Mariniello | Suporte usuários, testes (QA), documentação, treinamentos | 30h/semana (9 meses) | R$ 1.800,00 |

### 10.2 Interfaces com Outras Coordenações

**Coordenação Geral (Antonio Eduardo):**
- Aprovações estratégicas
- Representação junto à SETRE
- Decisões de governança

**Coordenação Administrativa/Financeira (Wilde):**
- Gestão orçamentária
- Contratações e pagamentos
- Prestação de contas

**Comunicação e Marketing (Vanêssa):**
- Plano de Comunicação (complementar a este documento)
- Campanhas de divulgação
- Produção de conteúdo

**Mobilização Social (Vinícius):**
- Identificação e cadastro de beneficiários
- Articulação com comunidades
- Suporte em oficinas

### 10.3 Modelo de Trabalho

**Regime:** Híbrido (remoto + presencial pontual)

**Reuniões Regulares:**
- **Equipe Técnica:** Semanal (2ª feira, 1h) - alinhamento operacional
- **Coordenação Geral:** Quinzenal (5ª feira, 1h) - apresentação de avanços
- **Multidisciplinar:** Mensal (última 6ª feira, 2h) - integração de todas as frentes

**Comunicação:**
- Assíncrona: WhatsApp (grupo equipe técnica)
- Síncrona: Google Meet (reuniões formais)
- Documentação: Google Drive (pasta compartilhada)

**Horário de Trabalho:**
- Flexível (equipe remota)
- Disponibilidade obrigatória: terças e quintas 14h-17h (overlap)
- Suporte aos beneficiários: seg-sex 8h-18h (escalonado)

---

## 11. ORÇAMENTO CONSOLIDADO

### 11.1 Investimento Total por Categoria

| **Categoria** | **Valor** | **% Total** |
|---|---|---|
| **Recursos Humanos (Equipe Técnica)** | R$ 108.600,00 | 18,7% |
| **Infraestrutura Tecnológica** | R$ 15.050,00 | 2,6% |
| **Custos Diretos (Oficinas, Eventos, Materiais)** | R$ 147.568,00 | 25,4% |
| **Equipamentos e Materiais Permanentes** | R$ 23.750,00 | 4,1% |
| **Custos Indiretos (Administrativo, Contábil)** | R$ 96.632,00 | 16,7% |
| **Outros (Mobilização, Diárias, Combustível)** | R$ 188.400,00 | 32,5% |
| **TOTAL GERAL** | **R$ 580.000,00** | **100%** |

### 11.2 Desembolso por Fase (Infraestrutura Tecnológica)

| **Fase** | **Item** | **Valor** | **Mês** |
|---|---|---|---|
| **Planejamento (Mês 4)** | Hospedagem (12 meses) | R$ 4.200,00 | Mês 4 |
| | Domínio | R$ 200,00 | Mês 4 |
| | Tema Premium | R$ 400,00 | Mês 4 |
| | Plugins Ano 1 | R$ 4.800,00 | Mês 4 |
| | CDN (12 meses) | R$ 2.400,00 | Mês 4 |
| | Storage (12 meses) | R$ 2.400,00 | Mês 4 |
| | Segurança (12 meses) | R$ 650,00 | Mês 4 |
| **TOTAL** | | **R$ 15.050,00** | |

**Observação:** Desembolso concentrado no Mês 4 para garantir infraestrutura operacional durante todo o desenvolvimento.

---

## 12. CRONOGRAMA VISUAL

```
MÊS 4 ████████ PLANEJAMENTO
      ├─ Requisitos
      ├─ Wireframes
      ├─ Contratações
      └─ Setup

MÊS 5 ████████ DESIGN
      ├─ Mockups
      ├─ Protótipo
      ├─ Testes Usabilidade
      └─ Guia de Estilo

MÊS 6 ████████ DESENVOLVIMENTO
      ├─ WordPress + WooCommerce
      └─ Marketplace (Dokan)

MÊS 7 ████████ DESENVOLVIMENTO
      ├─ Pagamentos
      ├─ Páginas
      └─ Beta

MÊS 8 ████████ CONTEÚDO EDUCATIVO
      ├─ LMS (LearnDash)
      ├─ Cursos
      └─ Biblioteca

MÊS 9 ████████ TESTES
      ├─ Funcional
      ├─ Performance
      └─ Segurança

MÊS 10 ████████ TESTES + PILOTO
       ├─ Acessibilidade
       ├─ Grupo Piloto (20-30 pessoas)
       └─ Ajustes

MÊS 11 ████████ LANÇAMENTO
       ├─ Go-Live
       ├─ Eventos (VDC + BC)
       └─ Marketing

MÊS 12 ████████ MANUTENÇÃO
       ├─ Suporte
       ├─ Coleta de Dados
       └─ RELATÓRIO FINAL ✅
```

---

## 13. ENTREGÁVEIS E MARCOS

### 13.1 Entregáveis Técnicos

| **#** | **Entregável** | **Prazo** | **Responsável** |
|---|---|---|---|
| 1 | Documento de Requisitos Funcionais | Mês 4, Semana 4 | Eduardo |
| 2 | Wireframes Aprovados (Figma) | Mês 4, Semana 4 | Rodrigo |
| 3 | Mockups Finalizados | Mês 5, Semana 4 | Rodrigo |
| 4 | Guia de Estilo (PDF) | Mês 5, Semana 4 | Rodrigo |
| 5 | Relatório de Testes de Usabilidade | Mês 5, Semana 3 | Eduardo + Rodrigo |
| 6 | Plataforma em Staging (Beta) | Mês 7, Semana 4 | Camillo + Eduardo |
| 7 | LMS Completo com Conteúdos | Mês 8, Semana 4 | Camillo |
| 8 | Relatório de Testes Completo | Mês 10, Semana 2 | Eduardo + Thyerry |
| 9 | Relatório de Piloto com Beneficiários | Mês 10, Semana 3 | Eduardo |
| 10 | Plataforma em Produção (Go-Live) | Mês 11, Semana 1 | Camillo + Eduardo |
| 11 | Materiais de Treinamento (vídeos, PDFs) | Mês 11, Semana 4 | Thyerry |
| 12 | **Relatório de Implantação da Plataforma** | **Mês 12, Semana 4** | **Eduardo (Coord. Técnico)** |
| 13 | Documentação Técnica Completa | Mês 12, Semana 4 | Eduardo + Camillo |

### 13.2 Marcos (Milestones)

| **Marco** | **Data Prevista** | **Critério de Aceitação** |
|---|---|---|
| M1 - Planejamento Concluído | Final Mês 4 | Stack contratada, wireframes aprovados |
| M2 - Design Aprovado | Final Mês 5 | Mockups validados, guia de estilo entregue |
| M3 - Beta Funcional | Final Mês 7 | Marketplace operacional em staging, pagamento testado |
| M4 - Conteúdo Completo | Final Mês 8 | LMS com 7 cursos, biblioteca com 30+ materiais |
| M5 - Testes Finalizados | Final Mês 10 | Todos os testes concluídos, piloto validado |
| M6 - Go-Live | Final Mês 11, Semana 1 | Plataforma no ar, eventos realizados, primeiras vendas |
| M7 - Projeto Concluído | Final Mês 12 | Relatório final entregue, metas cumpridas |

---

## 14. CONSIDERAÇÕES FINAIS

### 14.1 Fatores Críticos de Sucesso

1. **Engajamento dos Beneficiários:** A plataforma é inútil sem vendedores ativos. Mobilização (Vinícius) e suporte (Thyerry) são críticos.

2. **Usabilidade Impecável:** Público-alvo tem baixa letramento digital. UX simplificado (Rodrigo) e treinamentos práticos (oficinas Ação 5) são essenciais.

3. **Suporte Dedicado:** Primeiros meses pós-lançamento demandam suporte intensivo. WhatsApp e vídeos tutoriais são canais prioritários.

4. **Marketing Efetivo:** Atrair compradores é desafio. Integração com Plano de Comunicação (Vanêssa) e parcerias locais são fundamentais.

5. **Sustentabilidade Financeira:** Modelo de comissões deve ser validado. Busca de fontes complementares inicia no Mês 12.

### 14.2 Premissas do Plano

Este plano assume:
- Liberação pontual de recursos conforme cronograma de desembolso (Meses 1, 5, 9)
- Disponibilidade integral da equipe técnica conforme dedicação prevista
- Cooperação ativa dos beneficiários (participação em oficinas, testes, piloto)
- Acesso aos serviços contratados sem interrupções (hospedagem, plugins)
- Suporte dos parceiros institucionais (SETRE, prefeituras, MPT)

### 14.3 Próximos Passos Imediatos

**Ação 1: Aprovação Formal deste Plano**
- Apresentação à Coordenação Geral (Antonio) - 1 reunião (2h)
- Ajustes conforme feedback
- Envio para validação SETRE (se necessário)

**Ação 2: Reunião de Kickoff (Mês 4, Semana 1)**
- Convocação de toda equipe técnica
- Apresentação do plano em detalhes
- Definição de canais de comunicação
- Alinhamento de expectativas

**Ação 3: Contratações Imediatas (Mês 4, Semana 2)**
- Hospedagem (prioridade máxima)
- Domínio (registro imediato para evitar perda)
- Licenças plugins (pesquisa de melhores ofertas)

**Ação 4: Início das Atividades de Design (Mês 4, Semana 2-3)**
- Rodrigo inicia wireframes
- Eduardo + Vanêssa: workshop identidade visual (2h)

---

## 15. ANEXOS

### ANEXO A - Glossário Técnico

**WordPress:** Sistema de Gerenciamento de Conteúdo (CMS) open-source, base da plataforma

**WooCommerce:** Plugin de e-commerce para WordPress, transforma site em loja online

**Dokan:** Plugin marketplace multi-vendor, permite múltiplos vendedores na mesma plataforma

**LearnDash:** Plugin LMS (Learning Management System) para criação de cursos online

**CDN (Content Delivery Network):** Rede de servidores distribuídos geograficamente para entrega rápida de conteúdo

**SSL/HTTPS:** Certificado de segurança que criptografa comunicação entre navegador e servidor

**WCAG (Web Content Accessibility Guidelines):** Diretrizes de acessibilidade para conteúdo web

**LGPD:** Lei Geral de Proteção de Dados (Lei nº 13.709/2018)

**UX/UI:** User Experience (experiência do usuário) / User Interface (interface do usuário)

**SEO (Search Engine Optimization):** Otimização para mecanismos de busca (Google, etc.)

**NPS (Net Promoter Score):** Métrica de satisfação (escala 0-10)

**PWA (Progressive Web App):** Aplicativo web que funciona como app nativo

**Staging:** Ambiente de homologação (testes) idêntico à produção

**Backup Incremental:** Cópia apenas dos dados alterados desde último backup

### ANEXO B - Referências e Legislação

**Plano de Trabalho IDSB:** Termo de Fomento nº 021/2025 - SETRE/FUNTRAD

**Agenda Bahia do Trabalho Decente:** Decreto nº 13.149/2011

**PPA 2024-2027:** Lei nº 14.647/2023 (Programa 412 - Trabalho Decente)

**LGPD:** Lei nº 13.709/2018 (Proteção de Dados Pessoais)

**Marco Civil da Internet:** Lei nº 12.965/2014

**Estatuto da Pessoa com Deficiência:** Lei nº 13.146/2015 (Acessibilidade Digital)

**Documentação Técnica:**
- WordPress: https://br.wordpress.org/support/
- WooCommerce: https://woocommerce.com/documentation/
- Dokan: https://dokan.co/docs/
- LearnDash: https://www.learndash.com/support/docs/
- WCAG 2.1: https://www.w3.org/WAI/WCAG21/quickref/

### ANEXO C - Contatos da Equipe

| **Função** | **Nome** | **E-mail** | **Telefone** |
|---|---|---|---|
| Coordenador Técnico | Eduardo dos Anjos Pereira | [A PREENCHER] | [A PREENCHER] |
| Gestor de Desenvolvimento | Camillo Alves Marcarenhas | [A PREENCHER] | [A PREENCHER] |
| Designer UX/UI | Rodrigo Pena | [A PREENCHER] | [A PREENCHER] |
| Técnico de Suporte | Thyerry Pires Mariniello | [A PREENCHER] | [A PREENCHER] |
| Coord. Geral | Antonio Eduardo S. Moraes | moraes.edu@gmail.com | [A PREENCHER] |
| Coord. Administrativo | Wilde Soares Vieira de Souza | [A PREENCHER] | [A PREENCHER] |
| Comunicação | Vanêssa Pontes Chaves de Melo | [A PREENCHER] | [A PREENCHER] |
| Mobilização | Vinícius Martins de O. Gonçalves | [A PREENCHER] | [A PREENCHER] |

**Canais de Comunicação:**
- Equipe Técnica: WhatsApp [grupo a criar]
- Coordenação Geral: E-mail oficial IDSB
- Suporte Beneficiários: [A DEFINIR - WhatsApp Business + E-mail]

---

## APROVAÇÕES

Este Plano de Desenvolvimento da Plataforma REUNIR foi elaborado em conformidade com o Plano de Trabalho aprovado no Termo de Fomento nº 021/2025 (SETRE/FUNTRAD) e aguarda aprovação para início da execução.

| **Função** | **Nome** | **Assinatura** | **Data** |
|---|---|---|---|
| **Coordenador Técnico** | Eduardo dos Anjos Pereira | ________________________ | ___/___/2025 |
| **Coordenador Geral** | Antonio Eduardo Santos Moraes | ________________________ | ___/___/2025 |
| **Representante SETRE** | [Nome do Técnico Responsável] | ________________________ | ___/___/2025 |

---

**Instituto de Desenvolvimento Sustentável Baiano - IDSB**
Rua 2 de Julho, 225 – Centro, Edifício Minervina Freitas, 1º andar – Salas 101
Vitória da Conquista - BA | CEP: 45.000-240
Tel: (77) 3421-4907 | E-mail: idsb@idsb.org.br | Site: www.idsb.org.br

---

**Elaborado por:** Eduardo dos Anjos Pereira - Coordenador Técnico de Projeto
**Revisado por:** [A PREENCHER após revisão]
**Versão:** 1.0
**Data:** Novembro de 2025

*Este documento constitui parte integrante da execução do Termo de Fomento nº 021/2025 e será utilizado como referência para monitoramento, avaliação e prestação de contas junto à SETRE/FUNTRAD.*

---

**FIM DO DOCUMENTO**
