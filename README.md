# Obiettivo tracciatura activities

![This is an image](https://github.com/giorgiogrellalenavi/Activities/blob/dab6dfaa11cc42b2d2a02d787fc97a97afcf1040/Data/Images/Calendario_Annuale.JPG)

**Allenamento** – Adatta il tuo allenamento a seconda della distanza e dell’intensità delle gare imminenti. Dovrai allenarti anche al tuo passo gara per sviluppare la sensibilità all’andatura per la tua competizione. Includi lavori più brevi e più duri per aumentare il livello di intensità, nonché lavori più lunghi e più facili per migliorare la resistenza.
**Attiva** – Mantieniti pronto e riposato in questa fase, e recupera tra una gara e l’altra. Aumenta il carico di lavoro se le gare sono di meno e più distanziate nel tempo.
**Recupero** – In questa fase includi varietà, divertimento e qualunque andatura ti sembri giusta. Inserisci molto stretching. Resta in sintonia con il tuo sport facendo qualche lavoro continuo a un’andatura comoda.
**Preparazione** – Metti in primo piano un lavoro più lungo, più continuo. Lo scopo è quello di sviluppare una buona basa di esercizio fisico cardio e di adattare i muscoli ai movimenti specifici del tuo sport. Includi tanti esercizi per lo stretching, la flessibilità e il potenziamento.
# Activities stored in TCX files

The root element is a **TrainingCenterDatabase** element, which contains an **Activities** element. 

That element has one or more **Activity** elements, each describing an activity.

As well as some metadata, the Activity element contains a number of **Lap** elements. 

Each Lap element contains some metadata about the relevant lap (or split), 

as well as a **Track** element which contains many **Trackpoint** elements, 

each representing a data point that was reported by the device, 

and which may (or may not) contain, among other things, **time**, **latitude** and **longitude**, **altitude**, **heart rate**, **cadence**, **distance** and **speed** data. 

![This is an image](https://github.com/giorgiogrellalenavi/Activities/blob/c82c15d02e62a893e4074f230caae70925b38ec6/Data/Images/hierarchy_TCX_files.JPG)
