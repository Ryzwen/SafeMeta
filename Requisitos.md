1. Introdução

Este documento apresenta os requisitos funcionais e não funcionais da plataforma SafeMeta, além das personas, restrições e necessidades do contexto industrial.

2. Personas

Persona 1 — Carlos Mendes

Perfil

Operador de chão de fábrica.

Objetivos
-  Trabalhar com segurança;
-  Receber alertas preventivos;
-  Evitar penalizações.

Dores
-  Ambientes perigosos;
-  Falta de monitoramento preventivo;
-  Processos manuais.

Persona 2 — Fernanda Rocha

Perfil

Supervisora de segurança industrial.

Objetivos
-  Monitorar conformidade dos operadores;
-  Reduzir acidentes;
-  Receber alertas em tempo real.

Dores
-  Dificuldade em acompanhar múltiplos setores;
-  Dependência de fiscalização manual.

Persona 3 — Ricardo Alves

Perfil

Gestor industrial.

Objetivos
-  Melhorar indicadores de segurança;
-  Reduzir custos operacionais;
-  Garantir conformidade regulatória.

Dores
-  Falta de dados centralizados;
-  Baixa previsibilidade de riscos.

3. Requisitos Funcionais (RF)

| Código |	Requisito |
| :- | -: |
| RF01	| O sistema deve permitir cadastro de usuários |
| RF02	| O sistema deve permitir autenticação de usuários |
| RF03	| O sistema deve cadastrar EPIs |
| RF04	| O sistema deve monitorar operadores em tempo real |
| RF05	| O sistema deve detectar ausência de EPIs |
| RF06	| O sistema deve gerar alertas automáticos |
| RF07	| O sistema deve registrar ocorrências |
| RF08	| O sistema deve gerar relatórios de conformidade |
| RF09	| O sistema deve permitir consulta ao histórico |
| RF10	| O sistema deve gerenciar áreas de risco |
| RF11	| O sistema deve armazenar evidências visuais |
| RF12	| O sistema deve emitir notificações para supervisores |
| RF13	| O sistema deve gerar dashboards gerenciais |
| RF14	| O sistema deve classificar níveis de risco |
| RF15	| O sistema deve integrar sensores IoT |

4. Requisitos Não Funcionais (RNF)

| Código	| Requisito |
| :- | -: |
| RNF01	| O sistema deve possuir disponibilidade mínima de 99% |
| RNF02	| O tempo de resposta dos alertas deve ser inferior a 2 segundos |
| RNF03	| O sistema deve suportar múltiplos dispositivos simultaneamente |
| RNF04	| O sistema deve garantir criptografia dos dados |
| RNF05	| O sistema deve possuir escalabilidade horizontal |
| RNF06	| O sistema deve operar em ambiente web responsivo |
| RNF07	| O sistema deve possuir autenticação segura |
| RNF08	| O sistema deve manter logs de auditoria |
| RNF09	| O sistema deve suportar integração com câmeras IP |
| RNF10	| O sistema deve ser compatível com Docker |

5. Restrições do Sistema
-  Dependência de qualidade mínima das imagens capturadas;
-  Necessidade de conectividade estável;
-  Limitações de processamento em dispositivos edge;
-  Necessidade de treinamento dos modelos de IA;
-  Restrições regulatórias relacionadas à LGPD.

6. Fontes de Levantamento
-  Entrevistas fictícias com operadores;
-  Entrevistas fictícias com supervisores;
-  Benchmark de soluções industriais;
-  Pesquisa sobre segurança ocupacional.
