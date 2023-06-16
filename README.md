# Analysis of Software Aging in a Database Environment

**Autores:** Herderson Couto¹, Ermeson Andrade¹, Francisco Airton Silva², Gustavo Callou¹

**¹Universidade Federal Rural de Pernambuco (UFRPE) - Recife, PE - Brasil**

**²Universidade Federal do Piauí (UFPI) - Picos, PI - Brasil**

# Resumo gráfico
![alt text](https://github.com/herdersoncouto/softwareagingdatabase/blob/main/Resumo.png)

**Abstract** - Computer systems that run for long periods of time can suffer from a phenomenon known as software aging. Just like people, software can age. This phenomenon, however, can be viewed as a problem in computer systems because it can accelerate the depletion of resources and even lead to system failures. Databases are widely used software nowadays and can be affected by such a phenomenon, since they need to run for long periods of time uninterruptedly. Therefore, studies that investigate the possible effects of software aging in database environments are very necessary. In this work, we experimentally investigate the software aging phenomena in a database environment using PostgreSQL as the DBMS (Database Management System). By performing statistical analysis on the measurement data, we detected a suspicious phenomenon of software aging induced by workloads in memory and CPU usage. Additionally, our process analysis identified suspicious processes that can lead to memory degradations.

# Arquitetura utilizada

![alt text](https://github.com/herdersoncouto/softwareagingdatabase/blob/main/Cliente-Servidor.JPG)

# Scripts e plano de teste utilizado

Para visualizar os scripts utilizados no trabalho, bem como o plano de teste, [clique aqui](https://www.dropbox.com/scl/fo/zgcay0ymkfjnxz7zodane/h?dl=0&rlkey=n2ozc4b4e5fim7rc3has9bpgk).

**Intruções para execurtar os scripts de monitoramento:**

1 - Os scripts de monitoramento devem ficar no mesmo diretório;

2 - Excecutar script "startmonito.sh" para iniciar o monitoramento de memória RAM e CPU;

3 - Executar o script "startprocess.sh" para iniciar o monitoramento de processos.

**Intruções para uso do JMeter:**

1 - O plano de teste deve ser aberto pela ferramenta (JMeter 5.4.1); 

2 - Os parâmetros de teste devem ser alterados conforme a carga escolhida;

3 - Os dados dos testes serão salvos conforme o destino escolhido no na tabela de resultados. 
