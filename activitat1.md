Activitat 1
Es tracta de que feu un treball analitzant les principals característiques dels principals llenguatges de programació segons l'índex TIOBE que mesura la popularitat d'un llenguatge segons les referències que se'n fan a la Web.

Haureu d’escollir Python i Java, a més de 2 llenguatges més del TOP 20 que us resultin interessants, 4 llenguatges en total.

D'aquests llenguatges heu de comentar obligatòriament els següents aspectes:

Naixement, creadors i evolució històrica.
Característiques del llenguatge.
Imperatiu, declaratiu, OOP...
Compilat, interpretat, híbrid...
Principals novetats o aportacions respecte altres llenguatges.
Avantatges i inconvenients respecte altres llenguatges.
Principals entorns on es fa servir el llenguatge.
Exemple de codi (valoraré especialment si mostreu que ho heu implementat i provat).
Hola mòn (Molt fàcil de trobar).
Demanar el nom a l'usuari i mostrar-lo (haureu de buscar una mica més).
Buscar com estan les ofertes de treball a Infojobs del llenguatge.
WebGrafia.
Valoraré molt especialment que feu un treball personal, i que no us limiteu a enganxar informació trobada a Internet.

Intenteu entendre els termes tècnics que feu servir, i si teniu algun dubte podeu preguntar.

No serveix de res fer un treball que no entengueu vosaltres mateixos.

L’aspecte en un treball sempre és important.

Intenteu ser una mica polits, i sobretot, doneu un repàs a les faltes d'ortografia.

Podeu fer servir imatges rellevants.

#Python

- *Naixement, creadors i evolució històrica.*

A finals dels 80 Guido van Rossum va crear el llenguatje Python, va començar a implementarlo al decembre del 89 i el febrer del 91
va publicar la primera versio publica (0.9.0) la 1.0 al 94, la 2.0 al 2000 i la 3.0 al 2008.

fins el 2018 el desenvolupament de python ha estat dirigit per Guido van Rossum, amb la fundacio "Python Software Foundation". El juliol de 2018
Guido anuncia que deixara que dirigit el desenvolupament de python llavors des-de 2019 el desenvolupament de python ha estat dirigit per un consell de 5 membres escollits entre els desarrolladors de python y que cada any es renoven

- *Característiques del llenguatge.*

**Programacio orientada a Objectes**: aixo significa que el codi s'organitza en unitats denominades clases i objectes, aixo permet representar conceptes cotidians en un programa

**multiplataforma**: Aquest esta disponibles en els principals sistemes operatius.. Linux, Windows, Unix, MacOS... es a dir que aquest pot ser executat en casi cualsevol sistepa operatiu sempre i quan porti un interpret adequat

**Tipat Dinamic**: Aixo permet que les variables no tinguin que especificar el seu tipus, aquestes adopten un tipus en funcio del valor que se li assigne

**Open Source**: Python es un llenguatge de codi obert, per lo que no requereix de llicencies de pago per treballar amb ell

**Ampliament respatllat** Les sebes caracteristiques i funcionalitats fan que aquest llenguatge siqui molt interessant. Per aixo, python ha generat una comunitat d'usuaris molt gran al seu alrededor que pot ser utilitzada quan volem trovar informacio o demanar ajuda per desenvolupar el codi

- *Imperatiu, declaratiu, OOP...*

**Imperatiu** ja que li indiquem una secuencia de operacions que ha de realitzar

- *Compilat, interpretat, híbrid...*

**Llenguatge interpretat**: No es necessari compilar amb Python ja que els interpretes que utilitzen aquest llenguatge s'encarreguen d'executar els programes a traves d'escripts propis

- *Principals novetats o aportacions respecte altres llenguatges.*



- *Avantatges i inconvenients respecte altres llenguatges.*

Les principals avantatges de python son:

-Llenguatge "facil" d'utilitzar comparat amb altres llenguatges
-Es polivalent, es pot utilitzar per desenvolupar software, scrips de web, GUI d'escriptori, data science...
-Te una amplia coleccio de biblioteques i frameworks
-compatibilitat amb qualsevol sistema operatiu
-gratis i de codi obert
-comunitat molt forta 

i alguns dels inconvenients son

-alt consum de memoria
-lentitut
-el desenvolupament per a movil no es el seu fort

- *Principals entorns on es fa servir el llenguatge.*

python tot i que es pot fer utilitzar en molts entorns, principalment es fa utilitzar per desenvolupar llocs web i software automatitzacio de tasques, analisi de dades
i visualitzacio de dades 

- *Exemple de codi (valoraré especialment si mostreu que ho heu implementat i provat).*

**Aquest codi de python esta fet per mi, el vaig fer l'any passat a smx per el treball de final de curs on teniem un servidor i habiem de implementar serveis web, moodle, xarxa local amb dhcp dns... i una de les coses que tenia que fer jo era control·lar quan el processador passes de certa temperatura, tambe es un exemple de que amb python es pot fer un programa sencill amb poques linees**

```
import wmi
import time
from tkinter import messagebox

w = wmi.WMI(namespace= "root/OpenHardwareMonitor")
temperature_infos = w.Sensor()

def temperatura():
        for sensor in temperature_infos:
            if sensor.SensorType==u'Temperature':
                if sensor.Value > 60 and sensor.Name == ("CPU Core #2"):
                    messagebox.showerror("cpu safe temp exceded", "Please check the refrigeration system from the CPD or reboot the server, if the problem persists call the technician")
                   
                    
def init():
    while True:
        temperatura()
        time.sleep(15)

init()
```

- *Hola mòn (Molt fàcil de trobar).*

``` print("Hola Mon") ```

- *Demanar el nom a l'usuari i mostrar-lo (haureu de buscar una mica més).*

```
name = input("Enter your name: ")
print("Hello", name + "!")
```

- *Buscar com estan les ofertes de treball a Infojobs del llenguatge.*

![image](https://user-images.githubusercontent.com/95549844/192841068-ab464341-9625-43ba-9fb7-9bea2ddf1591.png)

aqui es veu que hi han moltes ofertes de treball buscan python i de segur cada dia en surten moltes mes

- *WebGrafia.*

https://www.mikedane.com/programming-languages/python/getting-user-input/
https://www.mclibre.org/consultar/python/otros/historia.html
https://keepcoding.io/blog/ventajas-y-desventajas-de-python/
https://similaranswer.es/para-que-se-usa-principalmente-python/

#Java

- *Naixement, creadors i evolució històrica.*



- *Característiques del llenguatge.*
- *Imperatiu, declaratiu, OOP...*
- *Compilat, interpretat, híbrid...*
- *Principals novetats o aportacions respecte altres llenguatges.*
- *Avantatges i inconvenients respecte altres llenguatges.*
- *Principals entorns on es fa servir el llenguatge.*
- *Exemple de codi (valoraré especialment si mostreu que ho heu implementat i provat).*
- *Hola mòn (Molt fàcil de trobar).*
- *Demanar el nom a l'usuari i mostrar-lo (haureu de buscar una mica més).*
- *Buscar com estan les ofertes de treball a Infojobs del llenguatge.*
- *WebGrafia.*

#C#

- *Naixement, creadors i evolució històrica.*
- *Característiques del llenguatge.*
- *Imperatiu, declaratiu, OOP...*
- *Compilat, interpretat, híbrid...*
- *Principals novetats o aportacions respecte altres llenguatges.*
- *Avantatges i inconvenients respecte altres llenguatges.*
- *Principals entorns on es fa servir el llenguatge.*
- *Exemple de codi (valoraré especialment si mostreu que ho heu implementat i provat).*
- *Hola mòn (Molt fàcil de trobar).*
- *Demanar el nom a l'usuari i mostrar-lo (haureu de buscar una mica més).*
- *Buscar com estan les ofertes de treball a Infojobs del llenguatge.*
- *WebGrafia.*

#SQL

- *Naixement, creadors i evolució històrica.*
- *Característiques del llenguatge.*
- *Imperatiu, declaratiu, OOP...*
- *Compilat, interpretat, híbrid...*
- *Principals novetats o aportacions respecte altres llenguatges.*
- *Avantatges i inconvenients respecte altres llenguatges.*
- *Principals entorns on es fa servir el llenguatge.*
- *Exemple de codi (valoraré especialment si mostreu que ho heu implementat i provat).*
- *Hola mòn (Molt fàcil de trobar).*
- *Demanar el nom a l'usuari i mostrar-lo (haureu de buscar una mica més).*
- *Buscar com estan les ofertes de treball a Infojobs del llenguatge.*
- *WebGrafia.*
