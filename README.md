**Калугин Антон Сергеевич**
==================================
ИП-20-7к
----------------------------------
Автомастерская
----------------------------------
![image](https://github.com/Unsympathetic/mash/assets/104492314/4053e202-62e1-4dee-8f58-ff70e57efd9b)

----------------------------------
```mermaid
erDiagram
  
 
    Klient ||--o{ Nakladnaya : places
    Klient {
        string name
        int Index
        string Address
        int Number
        string Email
    }
  
    Nakladnaya {
        string Name
        string Description
    }
Usluga ||--o{ Nakladnaya : places
    Usluga {
        string Name
        string Time
        string EdIzmer
 
    }
Postavchik ||--o{ Nakladnaya : places
  Postavchik {
    string Name
    int INN
    int Index
    string Addres
    string Email
   }

```
