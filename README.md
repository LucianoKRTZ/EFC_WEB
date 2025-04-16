EFC (Easy Finance Controller)

![Captura de tela 2025-04-16 105519](https://github.com/user-attachments/assets/95e97fad-6948-4717-9cd1-a4bfa11ab1bf)


O EFC (Easy Finance Controller) é uma aplicação web desenvolvida para ajudar pessoas a controlarem suas finanças pessoais de forma simples e eficiente.

📌 Visão Geral

O EFC permite:

    0 - Registrar entradas e saídas de valores
    1 - Categorizar transações
    2 - Visualizar gráficos comparativos
    3 - Analisar gastos por período e categoria

✨ Funcionalidades
    
    📝 Registro de Transações
    Entrada e saída de valores

Dados registrados:

    Data
    Valor
    Participante
    Descrição
    Categoria (Alimentação, Lazer, Transporte, etc.)

📊 Gráficos e Análises
*Comparativo por período (selecionável)

    Gráfico de Pizza:
        % do total gasto
        % investido
        % não movimentado

    Gráficos de Barras (Torre):
        Gastos por período
        Entradas por período
        Investimentos por período
        Gastos por categoria

🛠 Tecnologias Utilizadas

    Frontend:
        HTML5, CSS3, JavaScript
        Chart.js para visualização de dados

    Backend:
        Python (Flask)
        PostgreSQL (banco de dados)

🚀 Como Executar o Projeto

Pré-requisitos

    Python 3.11+

    pip

Instalação

    0 - Clone o repositório:
        git clone https://github.com/seu-usuario/EFC_WEB.git
        cd EFC_WEB
    
    1 - Instale as dependências:
        pip install -r requirements.txt

    2 - Execute a aplicação:
        python app.py

    3 - Acesse no navegador:
        http://localhost:5000
📂 Estrutura do Projeto

    EFC_WEB/
    ├── app.py                # Aplicação principal
    ├── finance.db            # Banco de dados SQLite
    ├── requirements.txt      # Dependências
    ├── static/
    │   ├── css/
    │   │   └── style.css     # Estilos CSS
    │   └── js/
    │       └── app.js        # JavaScript principal
    └── templates/
        ├── dashboard.html    # Página de dashboard
        └── index.html        # Página principal

📝 Roadmap

    0 - Versão inicial com registro de transações
    1 - Gráficos básicos
    2 - Exportação de relatórios (PDF/CSV)
    3 - Metas financeiras
    4 - Autenticação de usuários
    5 - Versão mobile

🤝 Como Contribuir

    0 - Faça um fork do projeto
    1 - Crie uma branch para sua feature (git checkout -b feature/AmazingFeature)
    2 - Commit suas mudanças (git commit -m 'Add some AmazingFeature')
    3 - Push para a branch (git push origin feature/AmazingFeature)
    4 - Abra um Pull Request

📄 Licença

    Distribuído sob a licença MIT. Veja LICENSE para mais informações.

✉️ Contato
    Luciano José Kratzer - @kratzer_luciano - www.linkedin.com/in/luciano-jose-kratzer


Link do Projeto: https://github.com/LucianoKRTZ/EFC_WEB
