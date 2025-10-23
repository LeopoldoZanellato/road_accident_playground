# \# Road Accident Playground Project

# 

# Este repositório contém um projeto de playground focado em acidentes de trânsito.

# 

# \## 1. Configuração do Ambiente

# 

# Siga estas etapas para configurar seu ambiente local e executar o projeto.

# 

# \### 1.1. Pré-requisitos

# 

# \* Python 3.8 ou superior

# 

# \* Git

# 

# \* Google Cloud SDK (para autenticação `gcloud`)

# 

# \### 1.2. Clonar o Repositório

# 

# Primeiro, clone o repositório do GitHub para sua máquina local:

# 

# ```

# git clone \[https://github.com/LeopoldoZanellato/road\_accident\_playground.git](https://github.com/LeopoldoZanellato/road\_accident\_playground.git)

# cd road\_accident\_playground

# 

# ```

# 

# \### 1.3. Criar um Ambiente Virtual

# 

# É altamente recomendado usar um ambiente virtual (como `venv`) para isolar as dependências do projeto.

# 

# \*\*Windows:\*\*

# 

# ```

# python -m venv venv

# .\\venv\\Scripts\\activate

# 

# ```

# 

# \*\*macOS / Linux:\*\*

# 

# ```

# python3 -m venv venv

# source venv/bin/activate

# 

# ```

# 

# \### 1.4. Instalar as Bibliotecas Necessárias

# 

# Com o ambiente virtual ativado, instale as bibliotecas Python necessárias:

# 

# ```

# pip install scikit-learn pandas xgboost joblib kfp google-cloud-aiplatform

# 

# ```

# 

# \*(Opcional: Se houver um arquivo `requirements.txt` no projeto, você pode usar `pip install -r requirements.txt`)\*

# 

# \### 1.5. Autenticação Google Cloud

# 

# Para interagir com os serviços do Google Cloud (como o AI Platform/Vertex AI), você precisa se autenticar. Execute o seguinte comando e siga as instruções no navegador:

# 

# ```

# gcloud auth login

# 

# ```

# 

# O ambiente agora está configurado e pronto para executar o projeto.

