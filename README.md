## Uzupełnianie zdań

1. Klasa to **szablon**.
1. Obiekt to **konkretny egzemplarz klasy**.
1. Zmienna to **pole, które definiujemy jako: typ nazwaZmiennej;. Tworzenie zmiennej dzielimy na 2 etapy - deklaracja i inicjalizacja**. 
1. Każda zmienna musi mieć określony **typ**, np. int, albo String.
1. Jeżeli deklarację zmiennej poprzedzimy słowem final, to **może być zainicjowana tylko raz, próba nadpisania wartości spowoduje błąd**.
1. W klasie mogą się znajdować **pola klasy, metody i konstruktory**.
1. **Konstruktory** są wywoływane przez operator **new** i służą do tworzenia nowych obiektów.
1. Jeśli w klasie zdefiniowano chociaż jeden **konstruktor** to kompilator nie wygeneruje dla nas **konstruktora** domyślnego.
1. Zakładając, że istnieje klasa Car, to przy zapisie:
````java
Car car1 = new Car(„BMW”, „M5”, 2007, 2.6);  
Car car2 = car1;​
````
car1 i car2 to dwie **referencje** wskazujące na ten sam **obiekt**.