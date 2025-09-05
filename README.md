# 📌 Funcionalidades do Sistema

# Resumo dos Módulos - Ecobin MVP

## 1. Autenticação & Gestão de Usuários (RF001-RF011)
- Cadastro de usuários (Pessoa e Empresa/ONG).
- Validação de CPF/CNPJ.
- Gestão de permissões por perfil.
- Recuperação e redefinição de senha com expiração de token.
- Alteração de dados sensíveis com senha.
- Tela de perfil com edição e upload de foto.

---

## 2. Sistema de Eventos & Inscrições (RF012-RF020)
- Criação, edição e cancelamento de eventos (apenas empresas).
- Inscrição de pessoas em eventos.
- Notificações sobre mudanças.
- Validação de presença via QR Code.
- Gestão de participantes e controle de inscrições.

---

## 3. Pontuação & Recompensas (RF021-RF027)
- Atribuição de pontos por eventos e reciclagem.
- Fórmulas com coeficiente βt para evitar inflação.
- Consulta de saldo e histórico (simulado).
- Catálogo estático de recompensas.
- Registro simulado de resgates.

---

## 4. IoT & Automação da Reciclagem (RF028-RF037)
- Cadastro de pontos de coleta.
- Integração com lixeiras inteligentes.
- Funcionamento em modo local (sem app) e conectado.
- Identificação de materiais por visão computacional (YOLO).
- Abertura/fechamento automático de tampas.
- Contagem e validação de descarte (imagem + peso).
- Cálculo automático e distribuição de pontos.

---

## 5. Sistema de Notificações (RF038-RF041)
- Envio de notificações por e-mail sobre eventos, pontos e reciclagem.
- Histórico completo de notificações acessível pelo usuário.

---

## 6. Comunidade & Fórum (RF042-RF046)
- Busca de empresas e eventos.
- Fórum vinculado exclusivamente a eventos.
- Interações: curtir, comentar, compartilhar.
- Gestão de postagens (editar/excluir).
- Exibição de número de interações.

---

## 7. Integrações & Sessões (RF047-RF052)
- APIs para comunicação com lixeiras inteligentes.
- Início, identificação de material e finalização de sessão.
- Autenticação segura de dispositivos.
- Encerramento manual ou automático de sessões.

---

## 8. Administração & Moderação (RF053-RF057)
- Painel administrativo com métricas e gráficos.
- Configuração do coeficiente βt.
- Gestão de pontos fixos de eventos.
- Antifraude: validação de cadastros únicos, logs de ações e validação de peso mínimo.

---
