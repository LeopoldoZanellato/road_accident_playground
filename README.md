# Road Accident Playground

Projeto de playground para experimentação com dados de acidentes de trânsito, focado em práticas do Vertex AI (Feature Store, Experiments e Pipelines).

## Visão geral

Este repositório contém exemplos e notebooks usados para aprendizado e testes com Vertex AI:
- explorer.ipynb — uso de Feature Store e Experiments  
- pipeline_teste — pipeline de exemplo (sem dados de treino)  
- segundo_pipline — pipeline completo com treino e teste

## Estrutura do repositório (resumida)

- explorer.ipynb
- pipeline_teste/
- segundo_pipline/
- README.md

## Pré-requisitos

- Python 3.8+
- Git
- Google Cloud SDK (gcloud) para autenticação
- Conta/projeto no Google Cloud com Vertex AI habilitado

## Configuração do ambiente

1. Clone o repositório:
   ```
   git clone https://github.com/LeopoldoZanellato/road_accident_playground.git
   cd road_accident_playground
   ```

2. Crie e ative um ambiente virtual.

Windows:
```
python -m venv venv
.\venv\Scripts\activate
```

macOS / Linux:
```
python3 -m venv venv
source venv/bin/activate
```

3. Instale dependências:
```
pip install scikit-learn pandas xgboost joblib kfp google-cloud-aiplatform
```
Ou, se existir, use:
```
pip install -r requirements.txt
```

## Autenticação Google Cloud

Autentique-se com:
```
gcloud auth login
gcloud config set project YOUR_PROJECT_ID
```
Substitua YOUR_PROJECT_ID pelo ID do seu projeto GCP.

## Uso rápido

- Abra e execute `explorer.ipynb` para explorar Feature Store e Experiments.
- Consulte as pastas `pipeline_teste` e `segundo_pipline` para exemplos de pipelines (scripts e YAMLs).
- Ajuste variáveis de projeto/endpoint nos scripts antes de executar no Vertex AI.

## Links úteis

- Feature Store: https://cloud.google.com/vertex-ai/docs/featurestore/latest/overview?hl=pt-br  
- Experiments: https://cloud.google.com/vertex-ai/docs/experiments/intro-vertex-ai-experiments?hl=pt-br  
- Pipelines: https://cloud.google.com/vertex-ai/docs/pipelines/introduction?hl=pt-br

## Observações

- Este repositório é voltado para aprendizado/prática — ajuste caminhos, nomes de bucket e permissões antes de rodar em produção.

