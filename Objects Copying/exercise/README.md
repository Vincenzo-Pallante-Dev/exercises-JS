# Object Copying

In this exercise we have created two objects: `person1` e `person2`. The object `person2` has been assigned to the object `person1`. You should modify the property `firstName` of the object `person2` in "Simon".

Write a comment explaining why, by modifying the object `person2`, also the object `person1` would be modified.

In questo esercizio abbiamo creato due oggetti: `person1` e `person2`. L'oggetto "persona2" è stato assegnato all'oggetto "persona1". Dovresti modificare la proprietà `firstName` dell'oggetto `person2` in "Simon".

Scrivi un commento spiegando perché, modificando l'oggetto `person2`, verrebbe modificato anche l'oggetto `person1`.

Spiegazione:
modificando l'oggetto `person2`, viene modificato anche l'oggetto `person1`.
perchè in questo caso sto applicando un pass by reference, ovvero:
i 2 oggetti puntano alla stessa posizione dei dati in memoria.
A differenza del pass by value che mi crea una copia senza influenzare
l'oggetto originale che punta in una differerente posizione dei dati in memoria
