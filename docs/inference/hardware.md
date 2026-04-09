# Hardware

## Configuracao utilizada

Os experimentos de inferencia foram executados em uma maquina local com a seguinte configuracao:

| Componente | Especificacao |
|---|---|
| **Processador** | AMD Ryzen 3 3200G |
| **GPU** | Radeon Vega 8 Graphics |
| **RAM** | 32 GB |
| **SO** | Windows 11 |
| **Runtime** | Ollama (execucao local) |

## Consideracoes

- O Ollama gerencia automaticamente o carregamento e descarregamento dos modelos
- Apenas um modelo e carregado em memoria por vez durante a inferencia
