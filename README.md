# 🍰 Casa de Doces Soares – Supabase + Lovable  

## 📌 Descrição do Projeto  
O projeto **Casa de Doces Soares** foi desenvolvido como parte da disciplina *Projeto de Banco de Dados*, integrando **Supabase** (banco de dados e back-end) e **Lovable** (front-end low-code). 

A aplicação tem como objetivo facilitar o **gerenciamento de pedidos e produtos** de uma confeitaria artesanal.  
Com ela, é possível **cadastrar, listar e controlar clientes, produtos e pedidos**, além de visualizar informações detalhadas de cada encomenda.  

---

## 📂 Estrutura do Repositório  

CasadeDocesSoares/
│
├── 📁 Diagrama/
│ └── Untitled.png # Modelo lógico do banco de dados
│
├── 📁 PrintTela/
│   ├── tela-inicial.png
│   ├── cadastro-usuario.png
│   ├── formulario-pedido.png
│   ├── pagamento.png
│   ├── produtos.png
│   ├── editar-pedido.png
│   └── meus-pedidos.png # Prints das telas da aplicação Lovable
│
├── 📁 ScriptSQL/
│ └── CasadeDocesSoares.sql # Script completo de criação do banco de dados (tabelas, views e função)
│
└── README.md # Documentação do projeto

---

## 🗄️ Banco de Dados – Supabase  

O banco foi criado em conformidade com a **3ª Forma Normal (3FN)**, garantindo integridade e organização dos dados.  

### Tabelas criadas:
- **usuarios** → cadastro de clientes  
- **produtos** → catálogo de produtos da confeitaria  
- **pedidos** → registro de pedidos e informações de entrega  
- **pedido_itens** → itens que compõem cada pedido  

### Extras:
- **View:** `view_pedidos_com_clientes` → Exibe pedidos com o nome do cliente.  
- **Função:** `calcula_total_pedido()` → Calcula o valor total de um pedido com base nos itens.  

📄 Arquivo SQL: [`ScriptSQL/CasadeDocesSoares.sql`](ScriptSQL/CasadeDocesSoares.sql)  
📊 Diagrama ER: [`Diagrama/Untitled.png`](Diagrama/Untitled.png)  


## 🚀 Tecnologias Utilizadas  

| Camada | Tecnologia |
|--------|-------------|
| Banco de Dados | **Supabase (PostgreSQL)** |
| Front-End | **Lovable** |
| Linguagem | **SQL** |
| Repositório | **GitHub** |

---

## 🎥 Vídeo de Apresentação  
O vídeo de demonstração do projeto deve apresentar:  
1. O banco de dados no Supabase (tabelas, view e função)  
2. As telas criadas no Lovable  
3. O fluxo principal da aplicação (cadastro e listagem de pedidos)  

## 🌐 Deploy  
🔗 [Acesse o site publicado aqui](https://abre.ai/casadedocessoares) 
🎬 Link do video :

---

## 👨‍💻 Autor  

**Projeto desenvolvido por Marcos André dos Santos Soares**  
---

⭐ *“Transformando doçura em tecnologia — um bolo por vez!”*
