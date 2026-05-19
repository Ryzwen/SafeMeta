```mermaid
flowchart LR

    Operador([Operador])
    Supervisor([Supervisor])
    Gestor([Gestor Industrial])
    IA([Serviço de IA])

    subgraph SafeMeta

        Login((Realizar Login))
        Monitorar((Monitorar Operador))
        Validar((Validar Uso de EPI))
        Alerta((Gerar Alerta))
        Ocorrencia((Registrar Ocorrência))
        Areas((Gerenciar Áreas de Risco))
        Relatorios((Consultar Relatórios))
        Alerta((Gerar Alerta))

        Monitorar -. include .-> Validar
        Validar -. extend .-> Alerta
        Alerta -.   include .-> Ocorrencia

    end

    Operador --> Login

    Supervisor --> Login
    Supervisor --> Monitorar
    Supervisor --> Areas

    Gestor --> Relatorios
    Gestor --> Alerta
    Gestor --> Areas

    IA --> Validar
    IA --> Alerta
