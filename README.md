Título do projeto - eCommerceInfoShipp 

Status do projeto (em desenvolvimento) - Etapa Inicial

Tecnologias que serão aplicadas (considere apenas as tecnologias abordadas no curso) - MySql, Apache-NetBeans, Git, GitHub, Figma, Draw.io .

Time de desenvolvedores - Administrador

Objetivo do software (a que deve servir)

  1° - Facilitar a Experiência do Usuário: Deve ser intuitivo e fácil de navegar, garantindo que os usuários possam encontrar, selecionar e comprar produtos ou serviços de forma rápida e sem complicações.

  2° - Gerenciar Transações de Forma Segura: Implementar métodos seguros para processamento de pagamentos, protegendo os dados dos usuários e cumprindo com as normas e regulamentações de segurança, como PCI-DSS.
      
  3° - Integrar Funcionalidades de Back-End: Deve incluir sistemas de gestão de inventário, controle de pedidos, atendimento ao cliente, e integração com outras ferramentas como ERPs, CRM, e sistemas de envio e logística.
      
  4° - Fornecer Suporte para Crescimento: O software deve ser escalável para suportar o crescimento do negócio, com a capacidade de lidar com um aumento no número de produtos, clientes e transações.
      
  5° - Oferecer Ferramentas de Análise e Relatórios: Permitir que os administradores acessem dados de vendas, comportamento do cliente e desempenho do site para tomar decisões informadas e otimizar a operação.
      
  6° - Personalização e Flexibilidade: Prover opções para personalização da interface e funcionalidades específicas, de acordo com as necessidades do negócio.
      
  7° - Otimização para SEO e Performance: Garantir que a plataforma seja otimizada para mecanismos de busca e que carregue rapidamente, melhorando a visibilidade e a experiência do usuário.
      
  8° - Suporte a Diversos Métodos de Pagamento e Moedas: Deve permitir que clientes utilizem diferentes formas de pagamento e realizem transações em diferentes moedas, se necessário.
      
  9° - Integração com Mídias Sociais e Marketing: Facilitar a integração com plataformas de mídia social e ferramentas de marketing para promover produtos, oferecer promoções e aumentar o alcance do negócio.
      
  10° -Manutenção e Atualizações Regulares: O software deve ser fácil de manter e atualizar, garantindo que esteja sempre seguro e compatível com as novas tecnologias e tendências de mercado.


Funcionalidades do sistema (requisitos) - 


 1. Requisitos Funcionais

A° - Catálogo de Produtos
            * Gestão de Produtos:
            * Adicionar, editar e remover produtos.
            * Gerenciamento de categorias e subcategorias.
            * Opção para incluir descrições, imagens, vídeos e especificações detalhadas.
            * Atualizar quantidades e preços com suporte a promoções e descontos.
            * Atributos Avançados do Produto:
            * Definir variações de produtos (tamanho, cor, etc.).
            * Exibir produtos "fora de estoque" e "em breve" com notificações opcionais de disponibilidade.
            * Monitoramento de Estoque:
            * Controle em tempo real e alertas automáticos para reabastecimento.
            * Compartilhamento e Avaliações de Produtos:
            * Opção para compartilhamento direto em redes sociais.
            * Sistema de avaliações e comentários de clientes.
            * Entrega e Logística:
            * Cálculo automático de frete baseado em localização e opções de envio.

B° - Página de Produto Individual
            * Exibição de Detalhes do Produto:
            * Galeria de imagens, vídeos e descrições interativas.
            * Exibição de variações disponíveis (tamanho, cor, etc.) e atualização automática do estoque.
            * Adicionar ao Carrinho:
            * Opção de adicionar ao carrinho com suporte a quantidade e variações.
            * Compartilhamento e Avaliações:
            * Exibir opções de compartilhamento e avaliações de outros clientes.

C° - Carrinho de Compras
            * Gestão do Carrinho:
            * Adicionar e remover produtos, ajustar quantidades e exibir total atualizado.
            * Cálculo automático de impostos e frete baseado na localização.
            * Aplicação de Cupons e Descontos:
            * Opção para inserir cupons de desconto com cálculo em tempo real.
            * Monitoramento de Estoque em Tempo Real:
            * Verificação de disponibilidade ao adicionar ou atualizar itens no carrinho.

D° - Checkout e Pagamento
            * Processo de Checkout Simplificado:
            * Opção de checkout como convidado ou logado.
            * Resumo de pedidos, total final e opções de entrega antes da confirmação.
            * Integração com Gateways de Pagamento:
            * Suporte para múltiplas moedas e métodos de pagamento (cartões, PayPal, boleto, etc.).
            * Pagamentos seguros com criptografia SSL.
            * Confirmação de Pedido e Notificações:
            * Confirmação de pedido via e-mail e notificação de status.
            * Integração com sistemas de rastreamento de pedidos.

E° - Conta do Cliente
            * Cadastro e Login:
            * Cadastro rápido e login seguro com opção de autenticação via redes sociais.
            * Recuperação de senha.
            * Gestão de Perfil do Cliente:
            * Edição de informações pessoais, endereços e preferências de notificação.
            * Histórico de Compras:
            * Visualização e rastreamento de pedidos anteriores.

F° - Gestão de Pedidos
            * Histórico e Detalhes de Pedidos:
            * Visualizar status de pedidos passados e em andamento.
            * Gerenciamento de endereços de entrega com opção de edição.
            * Gerenciamento de Inventário:
            * Controle de estoque em tempo real e alertas para produtos com baixo estoque.

G° - Sistema de Cadastro e Integrações
            * Cadastro de Clientes e Integrações:
            * Registro de novos clientes e login social.
            * Integração com transportadoras e cálculo de frete automático.
            * Integração com sistemas de e-mail marketing para comunicações.

H° - Página de Integrações e APIs
            * Integração com Sistemas de Terceiros:
            * Integração com plataformas de e-mail marketing, sistemas ERP e CRMs.
            * Integração com redes sociais para sincronização de produtos e promoções.
            * Suporte a Webhooks e APIs:
            * Notificações automáticas para eventos específicos (novo pedido, atualização de estoque).

I° - Painel de Relatórios e Análises
            * Relatórios e Indicadores de Desempenho:
            * Relatórios de vendas, clientes, produtos mais vendidos e categorias.
            * Análise de tráfego do site e conversões.
            * Gestão de Marketing e Promoções:
            * Gestão de cupons de desconto e ofertas sazonais.
            * Promoções de frete grátis e campanhas de marketing personalizadas.
      
      
      
2. Requisitos Não Funcionais
      * Escalabilidade:
      * Capacidade de suportar um aumento no número de usuários, produtos e transações sem perda de performance.
      * Desempenho:
      * Tempo de resposta rápido para carregamento de páginas.
      * Processamento eficiente de grandes volumes de dados.
      * Usabilidade:
      * Interface intuitiva e fácil de usar.
      * Design responsivo para dispositivos móveis.
      * Compatibilidade:
      * Suporte a diferentes navegadores e dispositivos.
      * Disponibilidade:
      * Uptime próximo de 100%.
      * Manutenibilidade:
      * Estrutura de código clara e bem documentada.
      * Facilidade de atualização e manutenção.
3. Requisitos de Segurança
      * Autenticação e Autorização:
      * Implementação de um sistema de login seguro.
      * Controle de acesso baseado em funções.
      * Proteção de Dados:
      * Criptografia de dados sensíveis.
      * Cumprimento das regulamentações de proteção de dados (como GDPR).
      * Prevenção de Fraude:
      * Monitoramento de transações suspeitas.
      * Implementação de CAPTCHAs e outros mecanismos de segurança.
      * Resistência a Ataques:
      * Proteção contra ataques DDoS.
      * Implementação de firewalls e outras medidas de segurança.
4. Requisitos Técnicos
      * Tecnologias de Front-End:
      * HTML5, CSS3, JavaScript, frameworks como React ou Angular.
      * Tecnologias de Back-End:
      * Linguagens como Python, Ruby, PHP ou Node.js.
      * Frameworks como Django, Ruby on Rails ou Express.js.
      * Banco de Dados:
      * Relacional (MySQL, PostgreSQL) ou NoSQL (MongoDB, Cassandra).
      * Integração com APIs:
      * Integração com serviços de pagamento, envio, e marketing.
      * Hospedagem e Infraestrutura:
      * Hospedagem em servidores cloud como AWS, Google Cloud ou Azure.
      * Uso de CDNs para melhorar a performance.
      * Versionamento e Controle de Código:
      * Uso de sistemas de controle de versão como Git.
      * Ambiente de desenvolvimento colaborativo, como GitHub ou GitLab.

