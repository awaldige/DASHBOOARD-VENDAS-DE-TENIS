# 📊 Dashboard de Vendas de Tênis — AW TECHNOLOGY

Dashboard desenvolvido para monitoramento e análise de vendas de tênis por loja, com visualização de indicadores comerciais e comparação de desempenho para apoiar a interpretação dos resultados.

O projeto simula um cenário de análise de dados comerciais, permitindo explorar informações sobre quantidade vendida, faturamento e desempenho das lojas.

## 🎯 Objetivo do Projeto

Transformar dados de vendas em informações visuais e organizadas, facilitando a análise de resultados e a identificação de oportunidades de melhoria no desempenho comercial.

## ✨ Funcionalidades

- 📈 **Quantidade de pares vendidos:** acompanhamento do volume de vendas por loja.
- 📅 **Filtro por período:** análise de vendas dentro de intervalos de datas.
- 💰 **Faturamento total:** visualização do valor total das vendas.
- 🏬 **Comparativo entre lojas:** análise do desempenho comercial de cada unidade.
- 📄 **Exportação de relatórios:** disponibilização dos dados para consulta externa, conforme a implementação.
- 📊 **Visualização analítica:** apresentação de dados e indicadores em formato visual.

## 📊 Dados Utilizados

A base de dados contempla campos relacionados às operações de venda:

| Campo | Descrição |
|---|---|
| ID da loja | Identificação da unidade comercial |
| Data da venda | Data em que a venda ocorreu |
| Quantidade vendida | Número de pares comercializados |
| Valor unitário | Preço por par de tênis |
| Valor total da venda | Valor total associado à operação |

Essas informações permitem calcular métricas de volume e faturamento e comparar o desempenho das lojas.

## 🛠️ Tecnologias Utilizadas

As tecnologias devem ser documentadas de acordo com a implementação real do projeto. A proposta atual contempla:

- **Python** — processamento dos dados e execução da aplicação, se utilizado.
- **Pandas** — manipulação e análise de dados, se utilizado.
- **Streamlit** — criação da interface do dashboard, se utilizado.
- **Excel/CSV** — armazenamento e importação dos dados, conforme os arquivos disponíveis.

## 📸 Prévia do Dashboard

Confira as imagens do projeto:

### Visualização 1

![Dashboard de vendas de tênis — visão 1](https://github.com/user-attachments/assets/b2e5948f-0528-4ad2-a7f3-4ab817836a12)

### Visualização 2

![Dashboard de vendas de tênis — visão 2](https://github.com/user-attachments/assets/3c57f23d-bdb1-43f5-afa3-4f28f6d1cce5)

### Visualização 3

![Dashboard de vendas de tênis — visão 3](https://github.com/user-attachments/assets/fe51eb4e-0d42-4766-b3c7-6c3431ef167b)

## 📥 Planilha de Dados

**[Baixar a planilha de vendas de tênis](planilha_vendas_tenis.xlsx)**

O link pressupõe que o arquivo `planilha_vendas_tenis.xlsx` esteja na raiz do repositório. Caso esteja em outra pasta, atualize o caminho.

## 📂 Estrutura do Projeto

```text
DASHBOOARD-VENDAS-DE-TENIS/
├── data/
├── scripts/
├── dashboard/
├── docs/
└── README.md
```

*Estrutura ilustrativa. Mantenha apenas as pastas e os arquivos que realmente existem no projeto.*

## 🚀 Como Executar o Projeto

Se a aplicação utilizar Python e possuir os arquivos indicados, siga os passos abaixo.

**1. Clone o repositório**

```bash
git clone https://github.com/awaldige/DASHBOOARD-VENDAS-DE-TENIS.git
```

**2. Acesse a pasta**

```bash
cd DASHBOOARD-VENDAS-DE-TENIS
```

**3. Instale as dependências**

Se o projeto possuir um arquivo `requirements.txt`:

```bash
pip install -r requirements.txt
```

**4. Execute o dashboard**

Se a aplicação possuir um arquivo `app.py`:

```bash
python app.py
```

Se for utilizado Streamlit, o comando normalmente será:

```bash
streamlit run app.py
```

Depois, abra no navegador o endereço indicado pelo terminal.

## 🔮 Melhorias Futuras

- Integração com banco de dados.
- Publicação do dashboard em uma plataforma de hospedagem.
- Inclusão de metas comerciais e indicadores de desempenho.
- Exportação de relatórios em Excel e PDF.
- Comparação de resultados entre diferentes períodos.
- Implementação de autenticação de usuários, caso necessária.

## 🤝 Contribuições

Sugestões e melhorias são bem-vindas.

1. Faça um fork do repositório.
2. Crie uma branch para sua alteração.
3. Faça as modificações e registre um commit.
4. Envie sua branch.
5. Abra um Pull Request.

## 👨‍💻 Autor

**André Waldige — AW TECHNOLOGY**

GitHub: [@awaldige](https://github.com/awaldige)

Projeto desenvolvido para estudo, prática de análise e visualização de dados e composição de portfólio profissional.

---

📊 **AW TECHNOLOGY — Tecnologia, dados e soluções digitais.**
