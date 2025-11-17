# Data Engineering Project – MkDocs Template

## 🚀 Visão Geral

Este projeto fornece uma estrutura base para:

- Organização clean de projetos de Engenharia de Dados  
- Documentação profissional utilizando **MkDocs + Material**  
- Boas práticas com **pre-commit**, **linting** e **formatação**
- Runners automatizados via **GitHub Actions**  
- Estrutura inicial para pipelines, scripts e containers Docker  

---

## 📁 Estrutura do Projeto

```
data-engineering-project/
│
├── data/
│   └── (arquivos de dados ou diretórios de origem)
│
├── docker/
│   └── (configurações de containers)
|
├── docs/
│   └── (arquivos-fonte da documentação)
│
├── scripts/
│   └── (scripts utilitários)
│
├── tests/
│   └── (testes unitários)
│
├── mkdocs.yml            # Configuração da documentação
├── pyproject.toml        # Configuração do ambiente Python
├── LICENSE
└── README.md
```

---

## 🧱 Arquitetura da Solução

![image](https://github.com/jlsilva01/projeto-ed-satc/assets/484662/541de6ab-03fa-49b3-a29f-dec8857360c1)

---

## 🛠️ Ferramentas e Tecnologias

- **Python 3.12+**
- **pytest**
- **Databricks**
- **Supabase**
- **Metabase**
- **Docker & Docker Compose**
- **MkDocs Material**
- **pre-commit**
- **GitHub Actions**

---

## 📚 Documentação

A documentação está configurada em MkDocs.  
Para rodar localmente:

```bash
pip install -r requirements.txt
mkdocs serve
```

Para gerar build estático:

```bash
mkdocs build
```

---

## 🧪 Testes

Execute os testes com:

```bash
pytest -v
```

---

## 🐳 Docker

Build da imagem:

```bash
docker build -t data-eng-project .
```

Rodar container:

```bash
docker run -it data-eng-project
```

---

## 👥 Autores

Substitua pelos participantes reais:

- **João Vitor** – Organização do Projeto – https://github.com/joaovfe
- **Eduardo** – Modelagem de Dados – https://github.com/EduarDomingos
- **Arthur** – Pipeline de Dados – https://github.com/Arthu085
- **Gabriel** – Dashboard – https://github.com/gabrieljloh
- **Gustavo de Freitas** – Documentação – https://github.com/Freitas86
- **Caroline** – Slides – https://github.com/

---

## 📄 Licença

Este projeto está licenciado sob os termos da licença **MIT**.  
Veja o arquivo `LICENSE` para mais detalhes.

---

## 🔗 Referências

Listar aqui: fontes, artigos, repositórios ou materiais utilizados no desenvolvimento.

