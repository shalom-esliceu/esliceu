## Quan tenim més d’un procés en marxa, el SO ha de planificar quin procés s’executa en cada moment

Planificador (Scheduler)

## Temps importants en la planificació de processos

Temps de resposta: quant triga el SO en donar-me servei

Temps de servei: temps que es triga en servir la petició

**Inclou el temps d’espera + el d’execució en CPU**

Temps de processador: temps de servei - temps d’espera a cua

Temps d’espera: temps a cua

Eficiència: temps de processador / temps total

Rendiment: processos executats per unitat de temps

## Segons com el SO assigna temps de de CPU a cada procés tenim els següents algoritmes de planificació:

FIFO: el primer que entra, el primer que surt

Round Robin: repartim el temps entre els processos que esperen

SJF: executem primer els processos més curts

SRT: primer els processos amb temps restant més curt

Prioritats

[Introducció](sistemas/Processos/Introducció.md)