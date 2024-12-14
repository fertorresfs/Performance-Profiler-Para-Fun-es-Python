# Performance-Profiler-Para-Fun-es-Python

## Como usar:

* Instalar memory_profiler: pip install memory_profiler
* Importar o decorador: from performance_profiler import profile_performance
* Decorar a função: @profile_performance
* Chamar a função normalmente.

## Explicação:

* O decorador profile_performance mede o tempo de execução usando timeit e o uso de memória usando memory_profiler.
* Os resultados são registrados usando o logging.
* O exemplo mostra como usar o decorador e como visualizar o uso de memória linha a linha com mprof.

## Melhorias:

* Relatório mais detalhado: Crie um relatório mais completo com gráficos e estatísticas.
* Outras métricas: Adicione métricas como uso de CPU, I/O, etc.
* Integração com outras ferramentas: Integre o profiler com outras ferramentas de profiling e monitoramento.
* Opções configuráveis: Permita que o usuário configure as métricas a serem coletadas e o nível de detalhe.
* Tratamento de erros: Adicione tratamento de exceções para lidar com erros durante a execução da função.
