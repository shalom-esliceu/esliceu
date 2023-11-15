## Crear un procés

Jerarquia de processos

PCB: Bloc de control de procés
### Informació necessària per a què el SO gestioni el procés
PID: Identificador del procés

L’estat del procés:  ready, run, wait...

PC: Comptador de programa

Registres de la UCP

Estadístiques

Informació de planificació

### Destruir un procés

Obre una aplicació, identifica el seu PID i executa la següent comanda des d’un terminal: kill -9 pid, on pid és l’identificador del procés.

Amb Ctrl+z el podem posar en background (bg backgroud, fg foreground)

Bloquejar/dormir un procés kill -STOP PID

Despertar un procés kill -CONT PID
