SafeMeta — Documentação de Design
O objetivo do protótipo é simular a experiência real de uso da plataforma de monitoramento inteligente de segurança industrial, permitindo validar fluxos operacionais, navegação e usabilidade antes da implementação do sistema.

Mapa de telas:
O fluxo principal da aplicação foi estruturado da seguinte forma:

Login

↓

Dashboard Principal

├── Gestão de EPIs

├── Alertas

├── Ocorrências

├── Relatórios

└── Áreas de Risco


Tela 1 — Login

Responsável pela autenticação dos usuários do sistema.

Usuários:
Operador
Supervisor
Gestor Industrial

Tela 2 — Dashboard Principal

Tela central do sistema.

Permite:
Visualizar indicadores em tempo real;
Monitorar operadores;
Consultar alertas ativos;
Acompanhar conformidade dos EPIs;
Acessar funcionalidades principais.

Tela 3 — Gestão de EPIs

Permite:
Cadastro de EPIs;
Consulta de equipamentos;
Controle de validade;
Associação de EPIs aos operadores.

Tela 4 — Alertas

Permite:
Visualizar alertas gerados pela IA;
Consultar nível de risco;
Ver evidências visuais;
Notificar responsáveis.

Tela 5 — Ocorrências

Permite:
Registrar ocorrências;
Consultar histórico;
Filtrar eventos por data, setor e risco.

Tela 6 — Relatórios

Permite:
Consultar indicadores;
Gerar relatórios de conformidade;
Analisar desempenho por setor;
Exportar informações.

Tela 7 — Áreas de Risco

Permite:
Gerenciar áreas críticas;
Visualizar zonas de risco;
Configurar níveis de criticidade.

Decisões de UX:
As decisões de experiência do usuário foram baseadas nas personas e necessidades identificadas durante a Sprint 1.

Interface voltada ao ambiente industrial

A aplicação foi projetada considerando:
Uso em tablets industriais;
Ambientes com baixa luminosidade;
Operadores utilizando luvas;
Necessidade de resposta rápida.

Por esse motivo foram adotados:
Botões grandes;
Alto contraste;
Poucos cliques para concluir tarefas;
Informações organizadas por prioridade.
Dashboard Centralizado

-O dashboard concentra os indicadores mais importantes do sistema.

Objetivo:
Reduzir o tempo necessário para localizar informações críticas e permitir acompanhamento em tempo real da operação.

-Hierarquia Visual de Alertas

Os alertas utilizam codificação por cores:
Verde → Conformidade
Amarelo → Atenção
Vermelho → Risco Crítico

Essa abordagem facilita a identificação imediata de situações que exigem ação.

-Navegação Simples

A navegação foi estruturada através de menu lateral fixo.

Benefícios:
Facilidade de aprendizado;
Menor carga cognitiva;
Acesso rápido às funcionalidades principais.

Mapeamento entre Telas e Casos de Uso
|Tela	| Caso de Uso Sprint 1|
|:-|-:|
|Login |	Realizar Login|
|Dashboard |	Monitorar Operador|
|Dashboard |	Validar Uso de EPI|
|Gestão de EPIs |	Cadastro de EPIs|
|Gestão de EPIs	| Consulta de EPIs|
|Alertas |	Gerar Alerta|
|Alertas |	Notificar Supervisor|
|Ocorrências |	Registrar Ocorrência|
|Ocorrências |	Consultar Histórico|
|Relatórios |	Consultar Relatórios|
|Relatórios |	Dashboard Gerencial|
|Áreas de Risco |	Gerenciar Áreas de Risco|
