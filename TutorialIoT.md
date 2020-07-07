Tutorial on how to build a system to prevent that a dog is taken from its owners


Dog Protection Against Stold

Maria Manuela de Queirós Ramos
md223ah

En App i mobilen för att få meddelande om hundens positionen har ändrats och/eller hunden har gått över gränsen för en area centrerad i den position hunden har lämnats.
En alarm ska startas ifall koppeln dras eller tas bort eller om gränsen ovan överskrids.
Temperatur och Relativ Fuktighet används för att se om hunden är ut eller in.
PyMakr eller GPS sensor kan användas.
WiFi används för att koppla till min mobiles Internet.
Ifall hunden ändå skulle tas från området som täcks av min telefon, så kan man ge GPS kredentialer till polisen.
Via min telefon kan jag se vilken position (Lat,  Long) som jag lämnar min hund på... sätter det som center på area ovan med att skicka positionen till programmet som körs i mikrokontrollen.

Om man har alla komponenter, FiPy, Pycom Board 3.0 samt sensorerna Temp, RH, GPS, Vibration, Knock samt Alarm, Transistor, Button och sätt att få GPSens data skickade till min telefon eller nåbar från polisen, så tar det bara någon timma att montera. Programen tar kanske några timmar att skapa, testa följde av att löda och testa. Kopplingen till t.ex. Ubidots, som har den area alarm som jag berättade om ovan tar kanske en timma med test.

Objective

Har haft problem med att inte kunna lämna min hund utanför t.ex. affärena. Någon har gjort så att min hund blev lös och kanske även blev tagen av någon. Han är gammal och blev lämnade på en park. 
Så tänkte att jag kunde skapa ett system med olika sensorer och alarm för att undvika att det händer igen. Det berättats att det hade hänt flera gånger på samma områd.
ICA har redan skapat en bur som ger alarm om någon försöker vidröra den. Jag tänkte göra en mindre lösning.

Man kan se hur mycket man vidrör hunden. Och se om man hittar någon som försöker ta hunden.


Material

Explain all material that is needed. All sensors, where you bought them and their specifications. Please also provide pictures of what you have bought and what you are using.

In this project I have chosen to work with the Pycom FiPy device as seen in Fig. 1, it’s a neat little device programmed by MicroPython and has several bands of connectivity. The device has many digital and analog input and outputs and is well suited for an IoT project.
I wanted to be able to test LTE 

I detta projekt valde jag att använda mig av FiPy mikrokontroller från Pycom som man ser i Fig 1.
Jag ville testa LTE och valde då FiPy istället för LoPy.
Man programmerar den med Micropython. Den har bägge analoga och digitala input och output och man kan koppla den på flera sätt: Bluetooth, LTE, Sigfox, LoRa, WiFi (inbyggd) och man kan använda sig av MQTT.

Fig 1![](https://i.imgur.com/Xfu2Xu3.jpg)

Fig 2![](https://i.imgur.com/DtAIATv.jpg)

List of material

| IoT Thing  | Beskrivning                |Pris     |
| -----------| -------------------------- | ---------- |
| FiPy       | Mikrokontroller från Pycom | 54 EUR     |
| Expansion Board 3.0  | Board från Pycom           | 16 EUR   |
| LTE-M Antenna Kit | Från Pycom             | 9 EUR |
| LoRa (868MHz/915MHz)  Sigfox Antenna Kit | Från Pycom | 9 EUR  |
| Alarm | Från Kjell  Company | 89.90 SWE |
| Lora Gateway | Från Connected Things(69 Pounds + ...) | 1150 SWE |




Fig 3![](https://i.imgur.com/RkD8acE.png)



Fig 4![](https://i.imgur.com/bW7zMIs.png)
 
Fig 5![](https://i.imgur.com/oahaMPG.png)

aaa
    What the different things (sensors, wires, controllers) do - short specifications
    Where you bought them and how much they cost






