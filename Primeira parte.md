\## 1. APRESENTAÇÃO ( Acho que falta uma contextualização do Projeto)



\### 1.1 Contextualização



O projeto insere-se nos eixos prioritários II (Erradicação do Trabalho Escravo) e VI (Trabalho Doméstico) da Agenda Bahia do Trabalho Decente, atendendo ao compromisso 004 do PPA 2024-2027: "Disseminar o Trabalho Decente como prevenção à precarização das relações e condições de trabalho".



Nos municípios de Vitória da Conquista e Barra do Choça, dados do Observatório da Erradicação do Trabalho Escravo (1995-2023) registram respectivamente 74 e 41 pessoas resgatadas de condições análogas à escravidão, concentradas majoritariamente no cultivo de café. Adicionalmente, 39,1% e 57,4% dos trabalhadores encontram-se sem carteira assinada, evidenciando vulnerabilidade social e necessidade de alternativas de geração de renda digna.



\## 2. ESCOPO TÉCNICO DO PROJETO



\#### 2.2.1 Para Beneficiários/Vendedores

\- Cadastro simplificado com dados básicos (CPF, endereço, tipo de produto/serviço comercializado)

\- Upload ilimitado de produtos com fotos, descrições e precificação

\- Dashboard de vendas com métricas individuais

\- Gestão de estoque e disponibilidade

\- Sistema de notificações (mensagens) \*\* Será realizado um sistema por mensagens via WhatsApp\*\*

\- Histórico de transações \*\* A transações serão feitas fora da plataforma, mas serão notificadas pelos próprios clientes/beneficiários \*\*



\#### 2.2.2 Para Compradores/Usuários



\- Navegação por categorias (Artesanato, Alimentos, Serviços, Outros)

\- Busca avançada com múltiplos filtros

\- Carrinho de compras

\- Sistema de mensagem automática via WhatsApp a loja do produto desejado

\- Sistema de avaliações e reviews



\## 3. ARQUITETURA DA SOLUÇÃO \*\* toda questão desse tópico, não consigo modificar, pois não tenho informações concretas e suficientes para alterar\*\*



3.2.1 Estrutura de Navegação (Sitemap) \*\* Até este momento que edito, está dessa forma no site (domingo, 16/11/2025 23:10\*\*

Inicio

├── Sobre o Projeto

│   ├── Plataforma REUNIR

│   ├── Novidades

│   ├── Parceiros em Destaque

│   ├── Informações Adicionais



├── Lojas

│   ├── Todos as lojas

│   ├── Categorias

│   │   ├── Categoria 1: Mais Recente

│   │   ├── Categoria 2: Mais Popular

│   │   └── Categoria 3: Aleatório

│   ├── Visite a Loja

|    ├── Produtos

│   │   ├── Nome do Produto

│   │   ├── Categoria 1: Ordenar por: Padrão

│   │   └── Categoria 2: Ordenar por: Popularidade

│   │   ├── Categoria 3: Ordenar por: Nota média

│   │   ├── Categoria 4: Ordenar por: Recente

│   │   └── Categoria 5: Ordenar por: Preço menor p/ maior

│   │   └── Categoria 5: Ordenar por: Preço maior p/ menor

│   └── Visualização Rápida

│   │   ├── Adicionar ao carrinho



├── Produtos

│   ├── Todos os Produtos

│   ├── Categorias

│   │   ├── Categoria 1: Mais Recente

│   │   ├── Categoria 2: Mais Popular

│   │   └── Categoria 3: Aleatório

│   ├── Visite a Loja

|    ├── Produtos

│   │   ├── Nome do Produto

│   │   ├── Categoria 1: Ordenar por: Padrão

│   │   └── Categoria 2: Ordenar por: Popularidade

│   │   ├── Categoria 3: Ordenar por: Nota média

│   │   ├── Categoria 4: Ordenar por: Recente

│   │   └── Categoria 5: Ordenar por: Preço menor p/ maior

│   │   └── Categoria 5: Ordenar por: Preço maior p/ menor

│   └── Negociar via WhatsApp



├── Aprenda \*\* Pendente \*\* 

│   ├── Oficinas

│   ├── Materiais Educativos

│   ├── Vídeos

│   └── \[PREENCHER outras seções]

├── Para Vendedores

│   ├── Detalhes da Conta



├── Minha Conta \*\* No caso, o Cliente\*\*

│   ├── Login/Registro

│   ├── Meus Pedidos

│   └── Favoritos



\#### 3.3.1 Gateway de Pagamento \*\* Os pagamentos até então serão feitos fora da plataforma, dependendo de cada beneficiário\*\* 



\#### 3.3.2 Logística e Envio \*\* A logística e o envio ficam dependentes do beneficiário, também.



\#### 3.3.3 Analytics e Monitoramento

\- Será feito através das reviews e avaliações feitas pelos usuários/cliente.

-- Será feito também através do feedback da conclusão, ou não da compra do produto/serviço pelo beneficiário.



\#### 3.3.4 E-mail e Notificações

\- As notificações serão encaminhadas para o WhatsApp cadastrado para a loja pelo beneficiário.



---





\## 4. DESIGN E EXPERIÊNCIA DO USUÁRIO \*\* Assim como no Tópico 3 não consigo modificar, pois não tenho informações concretas e suficientes para alterar, mas posso tentar adiantar certo pontos\*\*



\#### 4.4.1 Fluxo de Compra

```

\################



Fluxo do Cliente



-Acesso à Plataforma: O cliente navega pelo site/plataforma da REUNIR.



-Direcionamento a Lojas ou Produtos:

O cliente visualiza diferentes lojas/beneficiários ou busca diretamente produtos desejados.



-Seleção do Produto:

Cliente encontra o produto de interesse e acessa sua página detalhada.



-Contato via WhatsApp:

Na página do produto ou da loja, há um botão/ícone para conversar diretamente com o beneficiário/parceiro via WhatsApp.

O clique direciona para o aplicativo ou web do WhatsApp, iniciando uma conversa direta entre cliente e vendedor (beneficiário).



-Negociação e Compra:

O cliente pode tirar dúvidas, negociar detalhes, combinar entrega/formas de pagamento diretamente pelo WhatsApp.



-Conclusão da Compra:

Cliente confirma a compra (pagamento combinado fora do sistema).



-Avaliação e Review:

Após a finalização da compra e recebimento do produto/serviço, o cliente retorna à plataforma e deixa sua avaliação sobre o produto e a loja/beneficiário, contribuindo para a reputação e confiança no marketplace.



\#############################



Fluxo do Beneficiário/Parceiro



-Cadastro e Inserção de Produto:

O beneficiário acessa o painel de vendedor, cadastra o novo produto, informando descrição, fotos, estoque disponível e condições de venda.



-Disponibilidade e Viabilidade:

Mantém informações atualizadas sobre quantidade em estoque e disponibilidade para negociação rápida.



-Interação via WhatsApp:

Ao ser contatado por um cliente através do WhatsApp, responde dúvidas, oferece negociação, esclarece prazos e condições.



-Confirmação e Entrega:

Assim que o negócio está concluído (pagamento recebido/entrega combinada), o beneficiário marca o pedido como concluído na plataforma .



-Solicitação de Avaliação:

Pode solicitar gentilmente que o cliente faça sua avaliação, fortalecendo sua reputação dentro da plataforma.



\#### 4.4.2 Fluxo de Cadastro de Vendedor

```

-Preenchimento de formulário: Dados obrigatórios: nome completo, CPF, telefone, endereço, nome da loja, categoria da loja, produtos comercializados.

-Dados opcionais: foto da loja, breve descrição/biografia.

-Aprovação administrativa: Caso exigido, um moderador valida os dados/documentos e aprova o cadastro na área administrativa.

-Acesso à plataforma: O usuário será Cadastrado pela equipe Técnica, caso aprovado nos termos da plataforma.

-Acesso liberado: Após aprovação, o vendedor pode acessar o painel de vendedor, completar informações e iniciar cadastro de produtos.



```



\#### 4.4.3 Fluxo de Upload de Produto (Vendedor)

```

-Login no painel do vendedor: O vendedor acessa usando suas credenciais.

-Acesso ao módulo “Adicionar Produto”: Clica em “Novo Produto” ou “Adicionar Produto” no dashboard.

-Preenchimento de informações do produto:

Nome, categoria, preço, descrição detalhada, quantidade em estoque.

Upload de uma ou mais fotos/galeria de imagens (jpeg, png, tamanho máximo X Mb).

-Informações opcionais: tags, variações, atributos (cor, tamanho), vídeo de demonstração.

-Salvar/enviar para moderação: O produto é salvo em rascunho ou enviado para aprovação administrativa segundo política da plataforma.

-Produto ativo na loja: Produto fica disponível no marketplace com botão de compra, avaliações e rastreamento de estoque disponível.

-Notificações ao vendedor: Sistema envia confirmação de publicação/situação e instruções para acompanhamento de pedidos.```



