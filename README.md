# 📌 Funcionalidades do Sistema

## 1. Usuários & Autenticação
- Cadastro de usuário:
  - Pessoa física (CPF válido).
  - Empresa (CNPJ válido via API CNPJws, plano ativo).
  - ONG (CNPJ válido, sem fins lucrativos).
- Validação automática de CPF/CNPJ.
- Confirmação de e-mail no cadastro.
- Login e logout de usuário.
- Recuperação de senha via e-mail (token temporário).
- Edição de perfil (exceto CPF/CNPJ).
- Upload de foto de perfil.

---

## 2. Eventos & Inscrições
- Publicar evento (ONGs e empresas).
- Editar ou excluir evento (até 1h antes do início).
- Inscrição em eventos (usuário comum, respeitando limite de vagas).
- Explorar eventos com filtros:
  - Data.
  - Categoria.
  - Localidade.
  - Título ou palavra-chave.
- Notificações automáticas por e-mail:
  - Alterações.
  - Lembretes de presença.
- Validação de presença via **QR Code dinâmico**.
- Registro automático de pontos.
- Avaliação de eventos (1–5 estrelas + comentário).
- Cancelamento de inscrição (até 1h antes).
- Histórico de inscrições.

---

## 3. Comunidade & Fórum
- Criar posts (texto e imagem simples).
- Editar ou excluir posts próprios.
- Comentar em posts.
- Curtir, salvar e compartilhar conteúdos.
- Sistema de tags/categorias.
- Busca por tópicos, posts e perfis.
- Gestão de apelidos (nicks).
- Moderação de posts reportados:
  - Aprovar.
  - Ocultar.
  - Excluir.
- Painel de moderação com log de ações.

---

## 4. Gamificação (Sistema de Pontos & Recompensas)

### Sistema de Pontos
- Acúmulo automático em eventos e reciclagens.
- Aplicação do coeficiente **βt** para cálculo de pontos.
- Dashboard de pontos atualizado em tempo real.
- Histórico de pontos:
  - Ganhos.
  - Gastos.
- Integração com recompensas.
- Logs de auditoria (prevenção de fraude).

### Sistema de Recompensas
- Catálogo de recompensas:
  - Nome.
  - Descrição.
  - Custo em pontos.
  - Disponibilidade.
- Resgate de recompensas (com confirmação).
- Débito automático de pontos após resgate.
- Histórico de recompensas resgatadas.
- Relatórios para empresas:
  - Resgates realizados.
  - Ações que geraram pontos.
  - Alcance médio estimado.
- Empresas podem sugerir novas recompensas.
- Métricas de engajamento.

---

## 5. Geolocalização & Pontos de Coleta
- Lista dinâmica de pontos de coleta.
- Detalhes de pontos:
  - Nome.
  - Endereço.
  - Horário de funcionamento.
  - Contatos.
  - Tipo de acesso (público/privado).
- Cadastro de pontos por empresas/ONGs.
- Validação de dados obrigatórios.
- Integração com Google Maps/Waze:
  - “Abrir no mapa”.
- Diferenciação de acesso público/privado (ícone/tag).
- Indicação de disponibilidade (aberto/fechado).

---

## 6. Sistema de Notificações
- Envio de notificações por **e-mail via SMTP**.
- Histórico de notificações:
  - Paginado.
  - Filtros por data, evento, prioridade.
- Preferências de usuário:
  - Ativar/desativar tipos de notificações.
- Templates customizáveis de e-mail:
  - Variáveis dinâmicas.
  - Criação/edição/exclusão de templates.
  - Envio de testes.
- Integração com eventos de outros módulos:
  - Eventos, falhas, relatórios.
- Agrupamento em lote de notificações.
- Registro de falhas de envio e alertas.
- Painel administrativo para templates e monitoramento.

---

## 7. Busca & Filtros
- Busca textual avançada:
  - Insensível a maiúsculas/minúsculas.
  - Suporte a múltiplas palavras.
- Filtros por:
  - Área de atuação.
  - Localização.
  - Status.
- Paginação de resultados.
- Ordenação alfabética (A–Z / Z–A).
