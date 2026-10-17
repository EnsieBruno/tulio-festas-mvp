# Túlio Festas - MVP (Experiência Prática de Projeto de Software)

Aplicação web desenvolvida como Produto Mínimo Viável (MVP) para automatizar a triagem e o cálculo de orçamentos de serviços de bar e coquetelaria para eventos, resolvendo o gargalo de atendimento de microempreendedores individuais (MEI).

## 🚀 Sobre o Projeto
O projeto foi concebido para eliminar a demora comercial gerada por cálculos manuais e trocas demoradas de mensagens. Através de uma interface limpa e responsiva, o cliente final pode simular o custo do evento instantaneamente e ser redirecionado de forma automatizada para o WhatsApp do negócio.

## 🛠️ Tecnologias Utilizadas
- **Linguagem:** Python 3.11+
- **Microframework Web:** Flask 3.0+
- **Frontend:** HTML5, CSS3 responsivo (focado em acessibilidade)
- **Persistência:** Operação em memória (sem banco de dados relacional nesta fase de MVP)
- **Hospedagem:** Compatível com plataformas em nuvem (Render / PythonAnywhere)

## 📂 Estrutura do Repositório
```text
tulio-festas-mvp/
├── app.py              # Servidor Flask e rotas principais (Backend)
├── templates/
│   ├── index.html      # Tela 1: Landing Page Institucional
│   ├── simulador.html  # Tela 2: Simulador de Orçamentos (RF01, RNF02)
│   └── resultado.html  # Tela 3: Exibição do Valor e Link do WhatsApp (RF03)
├── static/
│   └── css/
│       └── style.css   # Estilos responsivos e diretrizes de acessibilidade (44x44px)
├── requirements.txt    # Dependências do projeto (Flask 3.0+)
└── README.md           # Documentação do projeto
