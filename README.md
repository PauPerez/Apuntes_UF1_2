# Apuntes_UF1_2
# Tipus de Software
- De sistema
    - Sistema Operatiu
    - Drivers
- D'aplicació
    - Suite ofimàtica
    - Navegador
    - altres
- De desenvolupament
    - Editors
    - Compiladors
    - Interprets
---
# Relació Hardware-Software
- **Disc dur**: Emmagatxema dades permanentment.
- **Memòria RAM**: Emmagatzema temporalment el codi binari de les dades.
- **CPU**: Llegeix i executa instruccions emmagatzemades en la RAM.
- **E/S**: Recull dades desde l'entrada, es mostren els resultats, s'emmagatzeman al disc...
---
# Codis Font, Objecte i executable
- **Codi font**: Arxiu llegible escrit en un llenguatge de programació.
- **Codi objecte**: Arxiu binari no executable.
- **Codi executable**: Arxiu binari executable
---
# Enginyería de software
- "Disciplina que estudia el desenvolupament i manteniment de software"

# Desenvolupament de software
- **ANÀLISI**
- **DISENY**
- **CODIFICACIÓ**
- **PROBES**
- **MANTENIMENT**
---
# Anàlisi
- Es determinen les necessitats del client i requeriments del software.
- l'especificació de requeriments ha de ser:
    - ser completa
    - ser concisa
    - Evitar ambiguitats
    - Evitar detalls o implementació
    - Ser entenible per el client
    - Separar requisits funcionals i no funcionals
    - Ordenar el model
    - Fixar criteris de validació
# Diseny
- S'organitza el sistema en elements que es poden desenvolupar individualment
- Especificar l'interrelació i funcionalitat dels elements
- Activitats habituals:
    - Disseny arquitectònic
    - Disseny detallat
    - Disseny de dades
    - Disseny d'interfície
# Codificació
- S'escriu el codi font de cada component
- Llenguatges utilitzats:
    - **Llenguatges de programació**: c, c++, Java...
    - **Llenguatges d'altre tipus**: HTML, XML, JSON...
# Probes
- Objectiu: Descobrir defectes del programa forçant-lo
- Fer-lo pasar per les maximes situacions diferents
# Manteniment
- És necessari realitzar canvis ocasionals
- S'haura de refer part del treball realitzat
- Tipus:
    - **Correctiu**: Es corregeixen defectes trobats al projecte
    - **Perfectiu**: Es canvia una funcionalitat per millorarla
    - **Evolutiu**: S'afegeixen funcionalitats noves
    - **Adaptatiu**: S'adapta a nous entorns
---
# Models de desenvolupament de software
- **Models clàsics**
    - **Model en cascada**: Amb aquest model no puc pasar al pas dos sense asegurarme 100% de que el pas 1 esta ben fet i acabat, així cada vegada que vull pasar al seguent pas.

    - **Model en V**: Amb aquest model a mesura que faig un pas, vaig comprobant per assegurarme de que està bé i el verifico per assegurarme que és vàlid, amb aquest model és facil adaptarse a diferents entorns.
    
    - **Prototips**: Molt sovint els requeriments no estan especificats clarament, es crea un prototip en la fàse d'analisi i es proba amb l'usuari per arribar a el que vol l'usuari. Es fa tantes vegades com calgui.
        - Prototips ràpids: Es pot fer com vulgi, només es una referencia per saber com es veuria, no s'aprofita en el futur.
        - Prototip evolutiu: Aquest prototip s'acaba utilitzant de base per al projecte final, per tant es desenvolupa amb les mateixes eines i llenguatge que aquest.
    
    - **Model en espiral**: Reutilitza bastant el codi, cada fase de desenvolupament segueix una sèrie de normes abans de pasar a la seguent i repetir el cicle.
    
    - **Metodologíes àgils**: Basades en el desenvolupament de software incremental els requisits i solucions del cual evolucionen amb el temps segons el que necessiti el projecte. Treball realitzat mitjançant la colaboració d'equips autoorganitzats. (Kanban, Scrum, XP).
        - Interaccions sobre processos i eines.
        - Documentació exhaustiva.
        - Negociació contractual amb el client.
        - Seguir un pla i tenir resposta de cara a canvis.
    - **Scrum**
        - Model de desenvolupament incremental.
        - Iteracions regulars.
        - Al principi d'aquestes s'estableixen les prioritats.
        - I al final de cada iteració s'obté una entrega parcial utilitzable per el client.
    - **XP**:
        - Simplicitat
        - Comunicació
        - Retroalimentació
        - Valentía
        - Respecte
---
# LLENGUATGES DE PROGRAMACIÓ
- **Obtenció de codi executable**: Compilació o interpretació.
- **Processos**: Compilació, Generació del codi objecte, anàlisi lèxic i sintàctic.
- **Llenguatges compilats**: C, C++
    - Execucuió molt eficient.
    - Però es necessari compilar cada vegada que es modifica el codi font.
- **Llenguatges interpretats**: PHP, JavaScript
    - El Còdi font es pasa de manera directa.
    - Però s'executa de manera menys eficient.
- **JAVA**
    - Es compila i s'obté el bytecode. (Com codi objecte però destinat a la màquina virtual de java)
    - Aquest bytecode és el que s'interpreta per executar-lo
--- 
# TIPOS
- **Declaratius**: Indiquem el resultat sense especificar el procés.
- **Imperatius**: Indiquem els pasos a seguir per obtenir un resultat.
- **Dificultat dels llenguatges**:
    - Baix nivell: ensamblador
    - Mig nivell: C
    - Alt nivell: C++, Java
---
# Evolució
- Codi binàri
- Ensamblaor
- Llenguatge estructurat
- Llenguatge orientat a objectes
---
# CRITERIS PER LA SELECCIÓ D'UN LLENGUATGE
- Camp d'aplicació
- Experiencia previa
- Eines de desenvolupament
- Documentació disponible
- Base d'usuaris
- Reutilabitzilitat
- Portabilitat
- Imposició del client
