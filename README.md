 ## ASL FabLab Castelfranco Veneto

Abbiamo utilizzato:
    
   **Scheda RaspberryPi**
   
   **Scheda Arduino Leonardo con:**
   -Lettore RFID-RC522 
     
![3](/IMAGES/3.jpg)
    


**RaspberryPi** = Il Raspberry Pi è un single-board computer sviluppato nel Regno Unito dalla Raspberry Pi Foundation. La scheda è stata progettata per ospitare sistemi operativi basati sul kernel Linux  o RISC OS
![1](/IMAGES/1.jpg)





**Arduino** = Arduino è una piattaforma hardware composta da una serie di schede elettroniche dotate di un microcontrollore. Con Arduino si possono realizzare in maniera relativamente rapida e semplice piccoli dispositivi come controllori di luci, di velocità per motori, sensori di luce, automatismi per il controllo della temperatura e dell&#39;umidità e molti altri progetti che utilizzano sensori, attuatori e comunicazione con altri dispositivi.
![2](/IMAGES/2.jpg)




## **SOFTWARE:**

* **Node-RED** è un software open source per programmare online contemporaneamente ad altre persone sullo stesso hardware creando dei &quot;flow&quot; a blocchi sfruttando principalmente Javascript, MQTT e JSON.
![4](/IMAGES/4.jpg)
      
 
 

## **SPIEGAZIONE**
   Tramite un iscrizione da un form google, i dati vengono scritti automaticamente in JSON in un sheet di google 
   e dopo aver ottenuto gli API KEY 
   (guida API KEY:
   https://help.risevision.com/hc/en-us/articles/115002245846-Generate-an-API-Key-for-the-Google-Spreadsheet-Widget) 
   questo foglio google da cui Node-Red può avere finalmente accesso, tramite i flussi condivisi in precedenza, caricherà 
   in un database questi dati, riempiendo delle tabelle per l'archiviazione. 
   Ogni persona registrata avrà una scheda magnetica, che utilizzerà per avere l'accesso ai macchinari 
   dichiarando data, ora e macchinario utilizzato.
















