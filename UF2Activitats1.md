# Activitats: 

Per dibuixar els diagrames de flux podeu fer servir [draw.io](https://draw.io) o qualsevol altra eina online.

1. Calcula el CC de les següents figures:
  - ![image](https://user-images.githubusercontent.com/110727546/204613022-4ab64342-2e06-438d-a7e8-570685b3c406.png)
  - ![image](https://user-images.githubusercontent.com/110727546/204613180-6d55bf09-28b8-417e-96f4-f71a762ac44c.png)
  - ![image](https://user-images.githubusercontent.com/110727546/204655229-8c3f28d7-3d8b-4746-a55d-331f89da39d2.png)

  - **Resultat 1:**
Complexitat ciclomàtica = nombre de branques – nombre de nodes + 2 = **16-14+2=4**
  - **Resultat 2:**
Complexitat ciclomàtica = nombre de branques – nombre de nodes + 2 = **16-14+2=4**
  - **Resultat 3:**
Complexitat ciclomàtica = nombre de branques – nombre de nodes + 2 = **8-6+2=4**

2. Dibuixa el diagrama de flux representat per aquest codi i després calcula la seva CC:

  - ![image](https://user-images.githubusercontent.com/110727546/204615125-363e5e6c-173b-4ec0-8c0b-cb97985ade06.png)

  - **Diagrama:**
![image](https://user-images.githubusercontent.com/113585932/204743693-4989729b-cc61-4de5-a8ca-729abd0953e3.png)

  - **Resultat CC:**
Complexitat ciclomàtica = nombre de branques – nombre de nodes + 2 = **8-7+2=3**
3. Dibuixa el diagrama de flux representat per aquest codi i després calcula la seva CC:

```
public class proves {
    public static  String queEmPoso(int temperatura) {
        String roba = "res";
        if(temperatura<0){
           roba = "roba d'esquiar";
        }
        else if(temperatura<10){
           roba = "roba de muntanya";
        }
        else if(temperatura<20){
           roba = "roba d'hivern";
        }
        else if(temperatura<30){
           roba = "roba d'estiu";
        }
        return roba;
    }    
}
```

  - **Diagrama:**

![image](https://user-images.githubusercontent.com/113585932/204748364-41e5819e-2594-41aa-a821-1d076dddc556.png)


  - **Resultat CC:**
Complexitat ciclomàtica = nombre de branques – nombre de nodes + 2 = **13-10+2=5**
4. Dibuixa el diagrama de flux representat per aquest codi, calcula la seva CC i crea una prova per a cada camí posible:

```
    public static Boolean llumsEncesos(int hora) {
        Boolean llums = false;
        if(hora <= 8 || hora >= 20){
            llums = true;
        }
        return llums;
    }
```
  - **Diagrama:**

![image](https://user-images.githubusercontent.com/113585932/206011899-f8be8f3f-1086-4a14-9ba2-1155a5e10065.png)

  - **Resultat CC:**
   Complexitat ciclomàtica = nombre de branques – nombre de nodes + 2 = **8-7+2=3**
  - **Resultat proves camins:**
  Prova 1: Hora = 7
  Prova 2: Hora = 16
  Prova 3: Hora = 22
5. Investiga sobre les proves de caixa negra:

  - Què són?
  - Quina diferència principal tenen sobre les de caixa blanca?
