# LavaJatoMaluco
Simulação de semaforo em Java

Este programa é uma simulação de resolução de problema de concorrencia utilizando a biblioteca semaforo do Java. Com ele é possivel resovler o problema de dois ou mais processos acessarem os recursos do processador. Como por exemplo:
Temos iniciados o Sistema Operacional o MS word, MS Exce e MS PowerPoint, todos estão iniciados mas somente um por vez tem acesso aos recursos do processador para executar determinadas tarefas, enquanto uma thread estiver utilizando os recursos as outras etarão em modo de espera ou dormindo, assim que os recursos são liberados, o  sistema permite que o proximo recurso tenha acesso aos recursos.

Semelhantemente aos exemplos acima, é o funcionamento do projeto LavaJatoMaluco. Nele temos 6 processos (carros) esperando para ter acesso ao recurso Cabine de Lavagem, enquanto um processo estiver em lavagem os demais estão dormindo. Quando os recursos são liberados, ele emite um sinal informando que está liberado e o proximo carro tem acesso a lavagem. Quando o ultimo processo termina de utilizar os recursos é disparado um sinal informando a disponibilidade, se não haver mais processo o sistema encerra o programa.

Como compilar e execultar o programa
