
<div align="center">
  <h4>Banco de Dados</h4>
  <img src="Vel.png" width="70px" align="center">
</div>

## 💡 Projeto

O banco de dados `virtual_easy_log` foi projetado para gerenciar as operações de uma plataforma de gestão para empresas de motos e restaurante. Este banco de dados cobre funcionalidades essenciais como: Associação das empresas com os planos, registro de empresa, entregador e coordenador, atribuição de pedidos e geração de comandas virtuais.

## 🔧 Tecnologias Utilizadas

- **BrModelo**: Utilizado para a criação dos modelos conceituais.
- **MySQL**: Utilizado para o gerenciamento de Banco de Dados Relacional.
- **SQL**: Linguagem utilizada para definir e manipular os dados no banco de dados.

## 🗃️ Estrutura do Banco de Dados

### 📊 Tb_Plano
Tabela para associar a empresa ao plano.

- **Colunas Principais**:
  - `Pk_id_Plano`

### 🏢 Tb_Empresa
Tabela para alocar a empresa.

- **Colunas Principais**:
  - `Pk_id_Empresa`

### 👨‍💼 Tb_Coordenador
Tabela para alocar o coordenador.

- **Colunas Principais**:
  - `Pk_id_Coordenador`

### 🛵 Tb_Entregador
Tabela para alocar o entregador.

- **Colunas Principais**:
  - `Pk_id_Entregador`

### 📈 Tb_Faturamento
Tabela para alocar o faturamento.

- **Colunas Principais**:
  - `Pk_id_Faturamento`

### 🛒 Tb_Pedido
Tabela para alocar o pedido.

- **Colunas Principais**:
  - `Pk_id_Pedido`

### 📄 Tb_Contrato
Tabela para alocar o contrato.

- **Colunas Principais**:
  - `Pk_id_Faturamento`

### Tb_Comanda_entregador

### Tb_Faturamento_empresa

