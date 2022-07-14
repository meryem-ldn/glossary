---
title: Containers
status: Completed
category: Tecnologia
---

## Cos'è
Un container è un processo in esecuzione con vincoli di risorse e capacità gestiti dal sistema operativo di un computer. I file disponibili per il processo del container vengono compressi in una "immagine" del container. I container vengono eseguiti in spazi di memoria adiacenti sulla stessa macchina, ma in genere il sistema operativo impedisce ai processi container separati di interagire tra loro.

## Quale problema affronta 
Prima che i container fossero disponibili, erano necessarie macchine separate per eseguire le applicazioni. Ogni macchina richiedeva il proprio sistema operativo, che occupava CPU, memoria e spazio su disco, il tutto per il funzionamento di una singola applicazione. Inoltre, la manutenzione, l'aggiornamento e l'avvio di un sistema operativo sono un'altra significativa fonte di lavoro.

## In che modo aiuta
I container condividono lo stesso sistema operativo e le relative risorse della macchina, distribuendo il sovraccarico delle risorse del sistema operativo e creando un uso efficiente della macchina fisica. Questa funzionalità è possibile solo perché i contenitori sono in genere limitati dall'essere in grado di interagire tra loro. Ciò consente di eseguire molte più applicazioni sulla stessa macchina fisica.

Tuttavia, ci sono dei limiti. Poiché i container condividono lo stesso sistema operativo, i processi possono essere considerati meno sicuri delle alternative. I contenitori richiedono anche limiti alle risorse condivise. Per garantire le risorse, gli amministratori devono vincolare e limitare l'utilizzo della memoria e della CPU in modo che le altre applicazioni non funzionino male.