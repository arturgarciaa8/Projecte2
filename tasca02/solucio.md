[T02_ Selecció d’un SAI per una empresa client Artur Garcia.md](https://github.com/user-attachments/files/22974297/T02_.Seleccio.d.un.SAI.per.una.empresa.client.Artur.Garcia.md)# Solució

[Uploading T02_ Selecció

1. **Inventari d’equips**

- Llista dels dispositius que es connectaran al SAI (ordinadors, monitors, router, etc.), justifiqueu si hi ha algun aparell que no hi connectareu al sistema d’alimentació ininterrompuda.

	4 ordinadors, 4 monitors i 1 router

- Consulta de les especificacions tècniques per obtenir el consum de cada dispositiu. Seleccioneu components que s’ajustin als que podríeu trobar-vos a la seu del client. Indiqueu clarament les dades del component triat i els valors de watts i VA corresponents.

	cost estimat de cada ordinador 200W  
	cost estimat de cada monitor 25w  
	cost estimat del router 10W

**2\.** **Càlcul de potència total**

- **Ordinadors:** 4 × 200W \= 800W  
- **Monitors:** 4 × 25W \= 100W  
- **Router:** 1 **×** 10W \= 10W  
- **Total:** 910W

Amb un marge de seguretat del 20%, la potència necessària és d’uns 1100W

**3\. Determinació de l’autonomia**

Es fixa un temps mínim de 10 minuts d’autonomia, suficient per guardar documents i apagar els equips de forma ordenada.

**4\. Models analitzats**

**APC Smart-UPS 2200VA**: 1980W, 12 minuts d’autonomia, preu 1100€, topologia line-interactive.

**Eaton 9PX 2200VA**: 2200W, 10 minuts, preu 1300€, topologia online (doble conversió).

**CyberPower PR2200VA**: 2200W, 9-10 minuts, preu 950€, line-interactive.

<img src="https://github.com/arturgarciaa8/Projecte2/blob/main/tasca02/img/tasca02.png?raw=true">

![][image1]

**5\. Informe tècnic**

## **1\. Càlculs realitzats**

### **Inventari i consum d’equips**

- **Ordinadors de sobretaula (4 unitats):** 200W cadascun → **800W**  
- **Monitors LED 24” (4 unitats):** 25W cadascun → **100W**  
- **Router:** 10W  
- **Impressora multifunció:** es descarta per consum elevat i no crític

**Total consum:**

800W+100W+10W=910W

### Reserva de seguretat (+20%) \= 1100W

### **Autonomia necessària**

Es fixa una autonomia mínima de 10 minuts, suficient per guardar documents i apagar correctament els equips.

## **2\. Models analitzats**

### APC Smart-UPS 2200VA (SMT2200RMI2U)

- Potència: 2200VA / 1980W  
- Autonomia: 12 min amb 1200W  
- Tipus: Line-interactive, ona sinusoidal pura  
- Sortides: 8x IEC C13, 2x IEC C19  
- Preu: 1100€

### Eaton 9PX 2200VA (9PX2200IRTN)

- Potència: 2200VA / 2200W  
- Autonomia: 10 min amb 1200W  
- Tipus: Online, doble conversió  
- Sortides: 8x IEC C13, 2x IEC C19  
- Preu: 1300€

### CyberPower PR2200ERT2U

- Potència: 2200VA / 2200W  
- Autonomia: 9-10 min amb 1200W  
- Tipus: Line-interactive, ona sinusoidal pura  
- Sortides: 8x IEC C13, 2x IEC C19  
- Preu: 950€

## **3\. Justificació de la selecció final**

El model seleccionat és el APC Smart-UPS 2200VA, per les següents raons:

- Cobertura suficient de potència: suporta fins a 1980W, molt per sobre dels 1100W necessaris.  
- Autonomia adequada: ofereix més de 10 minuts en la càrrega prevista.  
- Marca reconeguda: APC és un fabricant de confiança amb servei tècnic i recanvis fàcilment disponibles.  
- Relació qualitat-preu equilibrada: és més econòmic que l’Eaton (online), però amb millors prestacions i suport que el CyberPower.

##  **Conclusió**

Amb la instal·lació de l’APC Smart-UPS 2200VA, TecnoGestió S.L. disposarà d’una solució fiable per protegir els ordinadors, monitors i router davant possibles talls de subministrament elèctric, assegurant la continuïtat del servei i evitant pèrdua de dades.
