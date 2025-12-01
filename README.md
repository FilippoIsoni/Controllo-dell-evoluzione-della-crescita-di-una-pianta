Si vuole studiare l'evoluzione in altezza di una pianta, in funzione di due variabili di stato (altezza e umidità 
del suolo) e di un ingresso (irrigazione fornita). Il sistema proposto è un sistema di equazioni differenziali non 
lineari che cerca di modellizzare il problema catturandone le dinamiche fondamentali e introducendo notevoli 
semplificazioni: variabili quali temperatura, intensità luminosa, specie vegetale, non vengono ad esempio 
considerati.
1. Determinare il punto di equilibrio. 
Si calcolino i punti di equilibrio corrispondenti a uscita di equilibrio 𝑦̅ = 80𝑐𝑚 dato 𝐻𝑚𝑎𝑥= 100 cm. 
2. Linearizzazione del sistema 
Fissato il punto di equilibrio appena determinato: - - - 
Si linearizzi il sistema attorno al punto di equilibrio. 
Si discuta la stabilità semplice e asintotica del sistema lineare ottenuto e del punto di equilibrio 
considerato. 
Si calcoli la funzione di trasferimento W(s) del sistema linearizzato e se ne discuta la BIBO 
stabilità. 
3. Evoluzione del sistema allontanandosi dal punto di equilibrio 
Confrontare l’uscita del sistema linearizzato con quella originale, a seguito di una perturbazione delle 
condizioni iniziali (corrispondenti al punto di equilibrio), cioè un incremento del 5% dell’umidità del 
suolo (si intende un 5% relativo al valore di equilibrio calcolato, non un aumento del 5% in maniera 
assoluta). Spiegare i risultati alla luce dei punti precedenti.
4. Si vuole regolare la temperatura in modo che raggiunga un valore che favorisca la crescita della pianta. 
Si progetti la funzione di trasferimento di un controllore PID che garantisca: 
- Il sistema a catena chiusa di tipo 1
- |𝑒𝑟| ≤ 0,1, dove 𝑒𝑟 è l’errore a regime in risposta a un riferimento 𝑦0(𝑡) a rampa unitaria. 
- 𝑡𝑟 ≤ 𝑡𝑟 ∗ := 30 min, dove 𝑡𝑟è il tempo di salita della risposta indiciale del sistema a catena chiusa.
- 𝑀𝑝 ≤ 𝑀𝑝 ∗:= 20%, dove 𝑀𝑝 è la sovraelongazione della risposta indiciale del sistema a catena chiusa.
