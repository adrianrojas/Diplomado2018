# Concurrencia
### Nececidades

* Diseño simple
* Expresividad
* Eficiencia de ejecución
* Facilidad para depuración
* Escalabilidad y balanceo de cargas
* Diversidad de hardware

##### Pregunta loca
Tenemos un programa que puede ser dividido en 8 tareas separadas. Tenemos una máquina con 8 cores. El programa crea 4 threads.

**¿Son pocos o son muchos?**

```
Pues depende del estado actual del sistema.
```

## GCD

* 512k por thread vs 256 bytes que usa grand central dispatch.
* Normal queues (multiples threads).
* Dispatch es FIFO.
* Serial queues (un solo thread).
* Dispatch & terminación es FIFO.
* Encadenamiento.

**Todo el paralelismo es concurrente, pero podemos tener concurrencia sin paralelismo**










