# Modelowanie faktury VAT

| Termin oddania | Punkty     |
|----------------|:-----------|
|    05.11.2020 23:00 |  10        |

--- 
Przekroczenie terminu o **n** zajęć wiąże się z karą:
- punkty uzyskania za realizację zadania są dzielone przez **2<sup>n</sup>**.

--- 


Po zakupach w sklepie internetowym, klientowi na wskazany adres email, będzie wysłana faktura VAT. 
Twoim zadaniem jest napisanie logiki, która na podstawie zawartości koszyka z zakupami / produktami 
będzie generowała dane do faktury VAT, takie jak:
- Pozycje faktury, każda pozycja powinna składać się z:
    - Nazwy produktu
    - Ilości zamówionego towaru
    - Ceny jednostkowej netto
    - Ceny netto pozycji (cena jednostkowa razy ilość)
    - Podatek VAT
    - Wyliczona cena brutto
- Wartość całkowita faktury (suma cen brutto ze wszystkich pozycji)
- Dane klienta/sprzedającego:
    - Nazwa firmy
    - Adres
    - Numer NIP
    - Konto bankowe (sprzedający)
- Wygenerowany numer faktury
- Data wystawienia dokumentu
- Data sprzedaży
- Data zapłaty

Zaprojektuj zestaw klas, które zamodelują powyższy problem.

### Uwaga
Przed napisaniem każdej klasy stwórz dla niej odpowiednie testy jednostkowe, które klasa powinna spełniać. 
Wykorzystaj technikę Test Driven Design.
