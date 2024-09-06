# Gerenciador de Restaurantes

## Descrição
O Gerenciador de Restaurantes é uma aplicação dividida em duas partes: uma para o gerenciamento interno (web) e outra para a interação dos clientes (mobile). O objetivo é proporcionar uma solução completa para a administração do restaurante e uma experiência eficiente e agradável para os clientes.

## Funcionalidades

### Parte Web (Administração)

1. **Autenticação e autorização**
   - Login com diferentes níveis de permissão (gerente, garçom, cozinheiro).

2. **Gerenciamento de mesas**
   - Atribuir mesas aos garçons.
   - Visualizar status das mesas (ocupada, livre, aguardando pedido, aguardando pagamento).

3. **Gerenciamento de pedidos**
   - Visualizar e gerenciar pedidos em tempo real.
   - Notificar a cozinha sobre novos pedidos e alterações.
   - Alterar o status dos pedidos (em preparo, pronto, entregue).

4. **Gerenciamento da cozinha**
   - Visualizar pedidos pendentes e em preparo.
   - Alterar o status de itens nos pedidos.
   - Notificar garçons e clientes quando o pedido estiver pronto.

5. **Gerenciamento de entregas (delivery)**
   - Registrar e acompanhar pedidos de entrega.
   - Atribuir entregadores e monitorar status das entregas.

6. **Controle de estoque**
   - Gerenciar e monitorar o estoque de ingredientes e produtos.
   - Emitir alertas quando itens estiverem baixos.

7. **Cadastro de produtos e cardápio**
   - Adicionar, editar e remover itens do cardápio.
   - Definir preços, categorias e disponibilidade dos produtos.

8. **Relatórios gerenciais**
   - Visualizar relatórios sobre vendas, pedidos, consumo de estoque e produtividade dos funcionários.
   - Acompanhar métricas como faturamento diário, semanal e mensal.

9. **Gerenciamento de funcionários**
   - Registrar e gerenciar perfis de funcionários.
   - Atribuir turnos e tarefas.

10. **Notificações e alertas**
    - Enviar notificações para garçons quando clientes solicitarem atendimento.
    - Alertar a cozinha sobre modificações nos pedidos.

### Parte Mobile (Clientes)
Esse projeto terá uma vertente mobile, para os clientes poderem realizar pedidos diretamente do restaurante. No entanto, esse sistema ainda está em desenvolvimento.

## Tecnologias Utilizadas

- **Backend**: Laravel
- **Frontend Web**: Vue.js
- **Banco de Dados**: PostgreSQL

## Instalação

### Configuração do Backend (Laravel)

1. **Clone o repositório**
   ```bash
   git clone https://github.com/vncorrea/resSaas.git
   
2. **Navegue até o diretório do projeto**
```bash
cd resSaas

3. **Instale as dependências do Laravel**
```bash
composer install

4. **Configure o ambiente**
```bash
cp .env.example .env

5. **Gere a chave de aplicação do Laravel**
```bash
php artisan key:generate

6. **Execute as migrações do banco de dados**
```bash
php artisan migrate

7. **Inicie o servidor de desenvolvimento**
```bash
php artisan serve

8. **Instale as dependências do frontend**
```bash
npm install

9. **Inicie o servidor de desenvolvimento do frontend**
```bash
npm run dev
