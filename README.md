Sprint 1 — Exploração, Requisitos e Modelagem da Solução Metaindústria
Challenge 2026 — FIAP × SPI Integração

SafeMeta — Plataforma Inteligente de Segurança Industrial Proativa

Integrantes

-  Pedro Gonçalves - 557936
-  Lucas Baraldi - 555407
-  Lucas Zolla - 557952
-  Vitor Pantarotto - 554961

1. Problema Abordado

No contexto da Metaindústria, ambientes industriais modernos apresentam riscos constantes relacionados ao uso inadequado de Equipamentos de Proteção Individual (EPIs), exposição a áreas perigosas e ausência de monitoramento contínuo das condições de segurança operacional.

Os modelos tradicionais de segurança são predominantemente punitivos e reativos, atuando apenas após a ocorrência de infrações ou acidentes. Esse modelo gera:

-  Baixa eficiência na prevenção de acidentes;
-  Dependência excessiva de supervisão humana;
-  Falhas no acompanhamento em tempo real;
-  Dificuldade na geração de indicadores preventivos;
-  Alto risco operacional em ambientes industriais complexos.

2. Proposta de Solução

O projeto SafeMeta propõe uma plataforma inteligente de monitoramento e gestão de segurança industrial focada na prevenção de acidentes em tempo real.

A solução utiliza visão computacional, sensores industriais e inteligência artificial para identificar automaticamente:

-  Uso incorreto ou ausência de EPIs;
-  Entrada não autorizada em áreas de risco;
-  Situações críticas em campo;
-  Comportamentos inseguros;
-  Não conformidades operacionais.

Quando uma irregularidade é detectada, o sistema gera alertas instantâneos para supervisores e operadores, permitindo ação preventiva antes da ocorrência de acidentes.

Além disso, a plataforma mantém histórico operacional, relatórios de conformidade e indicadores estratégicos para gestão industrial.

3. Escopo da Aplicação

Atores do Sistema

Operador de Chão de Fábrica

  -  Responsável pelas atividades operacionais e uso obrigatório de EPIs.

Supervisor de Segurança

-  Responsável pelo monitoramento das ocorrências e resposta aos alertas.

Gestor Industrial

-  Responsável pela análise estratégica dos indicadores de segurança.

Sistema de IA

-  Responsável pela análise automatizada das imagens e eventos.

4. Funcionalidades Principais

-  Cadastro de usuários;

-  Cadastro de EPIs;

-  Monitoramento em tempo real;

-  Detecção automática de irregularidades;

-  Emissão de alertas;

-  Histórico de ocorrências;

-  Dashboard de conformidade;

-  Relatórios gerenciais;

-  Gestão de áreas de risco;

-  Registro de evidências visuais.

6. Tecnologias Selecionadas

| Tecnologia | Finalidade | Justificativa |
| :--- | :---: | ---: |
| Python | Backend e IA | Forte integração com IA e visão computacional |
| FastAPI | API REST | Alta performance e baixo tempo de resposta |
| PostgreSQL | Banco relacional | Confiabilidade e escalabilidade |
| OpenCV | Visão computacional | Processamento eficiente de imagens |
| YOLOv8 | Detecção de objetos | Reconhecimento de EPIs em tempo real |
| React | Frontend web | Interface moderna e responsiva |
| Docker | Containerização | Padronização de ambientes |
| MQTT | Comunicação IoT | Comunicação leve em tempo real |
| GitHub | Versionamento | Controle colaborativo do projeto |

7. Justificativa Técnica

A escolha tecnológica foi baseada nos requisitos de desempenho, confiabilidade e processamento em tempo real exigidos pelo ambiente industrial.

Python + FastAPI

Permitem desenvolvimento rápido de APIs robustas e integração nativa com bibliotecas de inteligência artificial.

OpenCV + YOLOv8

Viabilizam reconhecimento automático de EPIs e detecção de riscos com baixa latência.

PostgreSQL

Garante persistência confiável dos registros operacionais e relatórios históricos.

MQTT

Ideal para comunicação com sensores industriais e dispositivos IoT devido ao baixo consumo de banda.

Docker

Facilita implantação escalável em ambientes industriais híbridos.

8. Diagramas UML

Diagrama de Casos de Uso
-  Representa as interações entre os atores e as funcionalidades principais do sistema.

Diagrama de Atividades
-  Representa o fluxo operacional de detecção de irregularidade e emissão de alerta.

Diagrama de Classes
-  Representa a estrutura lógica do sistema, entidades, atributos e relacionamentos.

9. Diferenciais da Solução
-  Segurança preditiva;
-  Inteligência artificial aplicada à indústria;
-  Monitoramento contínuo;
-  Resposta em tempo real;
-  Gestão orientada por dados;
-  Escalabilidade industrial.

A plataforma SafeMeta atende aos objetivos do Challenge 2026 ao transformar o modelo tradicional de segurança industrial em um ecossistema preventivo, inteligente e orientado à tomada de decisão em tempo real.

A solução promove maior conformidade operacional, redução de acidentes e fortalecimento da cultura de segurança dentro do ambiente Metaindústria.
