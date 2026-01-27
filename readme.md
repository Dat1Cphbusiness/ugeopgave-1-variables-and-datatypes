Velkommen til den første dag med ugeopgaver.
Øvelserne skal afleveres inden dagen er omme. Man afleverer ved at indsætte et link til sit eget repository. 
Et repository er som en mappe du har i skyen (GitHub) med din besvarelse i. Hver torsdag skal du starte med at lave et nyt repository til dagens besvarelse, og hver torsdag skal du aflevere linket til det nye repository.
Hvis du ikke allerede har en, skal du i dag starte med at lave en GitHub konto og dernæst et repository til dagens aflevering (se Task 1).

Det er lidt omstændigt første gang, men som alt andet her i livet - det bliver lettere når du har gjort det nogle gange.
Alle opgaverne skal laves individuelt, men I opfordres til at hjælpe hinanden.

## Opret et github repository

**Opgave:**
til at lægge dine øvelser i.

1. Lav en bruger på https://github.com
2. Vælg fanebladet repositories
3. Lav et nyt repository med navnet "ugeopgave1-variable". Scroll ned og sørg for at Add README er slået til
4. Du ser nu indholdet af dit nye repository, der ligger kun en fil: "README.md" 
5. Tryk på den grønne knap og kopier adressen til dit repository. Den ligner noget i stil med dette:
   https://github.com/DitGitNavn/DitRepoNavn.git
5. Åbn IntelliJ og vælg File > New > Project from version control.
6. Indsæt den kopierede adresse til dit repository i URL feltet. Vælg hvor dit repo skal ligge i lokalt i feltet nedenunder.
6. Klik på Clone knappen. Du har nu "klonet" dit repository ned til din lokale maskine, og til højre skulle du gerne nu se README.md filen.
7. Åbn filen og skriv dit navn og email adresse.
8. Hvis intelliJ viser filnavnet med rød skrift, betyder det at den IKKE er med i versionsstyring. Højreklik på den vælg Git > Add
9. Nu skal du comitte filen. I IntelliJ's topmenu, vælg Git > Commit.
10. Du ser nu readme filen, med et tekstområde under. Her skal du skrive et summary fx. "første commit"
11.  I IntelliJ's topmenu, vælg Git > Push.
12. I browseren finder du tilbage til dit repository på github. Noget i stil med dette: https://github.com/DitGitNavn/DitRepoNavn
Du skal nu kunne se din ændring af readme filen, der viser dit navn og email. (du behøver ikke at åbne filen for at se det)


Brug for hjælp til Github? 

- [getting started](https://docs.github.com/en/github/getting-started-with-github/create-a-repo)
- [comitting](https://docs.github.com/en/desktop/contributing-and-collaborating-using-github-desktop/committing-and-reviewing-changes-to-your-project)



## Lav variable til Real-World Scenarios

**Opgave:**
1. Start en nyt projekt. 
2. Opret en folder med navnet 'src' i projektet
3. Lav en klasse i src folderen. Du bestemmer navnet på klassen.
4. Skriv en main metode i klassen.

I det følgende skriver du al din kode i main metoden. Når du er færdig med en opgave kan du _udkommentere_ det hele og starte på den næste nedenunder.
```java 
//opgave 1

/*
  udkommenteret besvarelse på opgave1 her
*/

//opgave 2
```


### Opgave 1: Shopping cart
**Opgave:**

Erklær variable for prisen på tre varer (fx. 25.50, 15.00 og 30.00).  
Erklær en variable for subtotalen (summen af de tre varer).  
Erklær en variable for momsprocenten (fx. 25.0).  
Erklær en variable for den samlede pris inklusiv moms.  
Udskriv subtotalen og den samlede pris med moms.

<details>
<summary>Hjælp</summary>
<detail>

1. Erklær `double item1 = 25.50`
2. Erklær `double item2 = 15.00`
3. Erklær `double item3 = 30.00`
4. Erklær `double subtotal = item1 + item2 + item3`
5. Erklær `double taxRate = 25.0`
6. Erklær `double withTax = subtotal + (subtotal * taxRate / 100.0)`
7. Print `subtotal` og `withTax`
   
</detail>
</details>

**Forventet Output:**
```
70.5
88.125
```

---

### Opgave 2: Split restaurant bill
**Opgave:**

Erklær variable for mad (fx. 450.0), drikkevarer (fx. 120.0), drikkepenge (fx. 50.0) og antal personer (fx. 4).  
Erklær en variable for den samlede regning.  
Erklær en variable for beløbet pr. person.  
Udskriv beløbet pr. person.

<details>
<summary>Hjælp</summary>
<detail>

1. Erklær double `foodTotal = 450.0`
2. Erklær double `drinks = 120.0`
3. Erklær double `tip = 50.0`
4. Erklær int `people = 4`
5. Erklær double `grandTotal = foodTotal + drinks + tip`
6. Erklær double `perPerson = grandTotal / people`
7. Print `perPerson`
   </detail>
</details>

**Forventet Output:**
```
155.0
```

---

### Opgave 3: Discount calculation
**Opgave:**

Erklær en variable for den oprindelige pris (fx. 300.0).  
Erklær en variable for rabatprocenten (fx. 20.0) og beregn prisen efter rabat.  
Erklær en variable for momsprocenten (fx. 25.0) og beregn den endelige pris inklusiv moms.  
Udskriv den oprindelige pris, prisen efter rabat og den endelige pris.

<details>
<summary>Hjælp</summary>
<detail>

1. Erklær `double originalPrice = 300.0`
2. Erklær `double discountPercent = 20.0`
3. Erklær `double discounted = originalPrice - (originalPrice * discountPercent / 100.0)`
4. Erklær `double taxPercent = 25.0`
5. Erklær `double finalPrice = discounted + (discounted * taxPercent / 100.0)`
6. Print `originalPrice`, `discounted` og `finalPrice`
   </detail>
</details>


**Forventet Output:**
```
300.0
240.0
300.0
```

---

### Opgave 4: Party planning
**Opgave:**

Du planlægger en fest. Erklær variable for antal gæster (fx. 15) og antal cupcakes (fx. 40).  
Erklær en variable for hvor mange cupcakes hver gæst får (brug division).  
Erklær en variable for hvor mange cupcakes der er til overs (brug modulo).  
Udskriv hvor mange cupcakes hver gæst får og hvor mange der er til overs.

<details>
<summary>Hjælp</summary>
<detail>

1. Erklær `int guests = 15`
2. Erklær `int cupcakes = 40`
3. Erklær `int cupcakesPerPerson = cupcakes / guests`
4. Erklær `int leftover = cupcakes % guests`
5. Print "Each guest gets " + cupcakesPerPerson + " cupcakes"
6. Print leftover + " cupcakes left over"
   </detail>
</details>

**Forventet Output:**
```
Each guest gets 2 cupcakes
10 cupcakes left over
```

---

### Opgave 5: Build greeting message
**Opgave:**
Opret en StringBuilder til at bygge en hilsen.  
Erklær variable for et navn (fx. "Anna") og en alder (fx. 25).  
Brug append-metoden til at tilføje tekst stykke for stykke: "Hello, ", navnet, "! ", "You are ", alderen og " years old."  
Udskriv den samlede tekst.

<details>
<summary>Hjælp</summary>
<detail>

1. Opret en StringBuilder: `StringBuilder sb = new StringBuilder()`
2. Erklær `String name = "Anna"`
3. Erklær `int age = 25`
4. `sb.append("Hello, ")`
5. `sb.append(name)`
6. `sb.append("! ")`
7. `sb.append("You are ")`
8. `sb.append(age)`
9. `sb.append(" years old.")`
10. Print `sb.toString()`
    </detail>
</details>


**Forventet Output:**
```
Hello, Anna! You are 25 years old.
```

---




### Opgave 6: Using +=
**Opgave:**

Erklær en variable for en score (fx. 100).  
Udskriv scoren.  
Læg 50 til scoren ved at bruge += operatoren og udskriv igen.  
Læg 25 til scoren og udskriv igen.

<details>
<summary>Hjælp</summary>
<detail>

1. Erklær int `score = 100`
2. Print `score`
3. `score += 50`
4. Print `score`
5. `score += 25`
6. Print `score`
   </detail>
</details>

**Forventet Output:**
```
100
150
175
```

---

### Opgave 7: Using -=
**Opgave:**

Erklær en variable for liv/health (fx. 100).  
Træk 15 fra ved at bruge -= operatoren (spilleren tager skade) og udskriv.  
Træk 20 mere fra (mere skade) og udskriv igen.

<details>
<summary>Hjælp</summary>
<detail>

1. Erklær int `health = 100`
2. `health -= 15`
3. Print `health`
4. `health -= 20`
5. Print `health`
   </detail>
</details>


**Forventet Output:**
```
85
65
```

---

### Opgave 8: Using *=
**Opgave:**

Erklær en variable for en pris (fx. 50.0).  
Udskriv prisen.  
Fordobl prisen ved at bruge *= operatoren og udskriv igen.

<details>
<summary>Hjælp</summary>
<detail>

1. Erklær double `price = 50.0`
2. Print `price`
3. `price *= 2`
4. Print `price`
   </detail>
</details>

**Forventet Output:**
```
50.0
100.0
```

---

### Opgave 9: Increment og decrement med 1
**Opgave:**

Erklær en variable for en tæller (fx. 10).  
Udskriv tælleren.  
Brug ++ operatoren til at øge tælleren med 1 og udskriv igen.  
Brug -- operatoren til at mindske tælleren med 1 og udskriv igen.

<details>
<summary>Hjælp</summary>
<detail>

1. Erklær int `counter = 10`
2. Print `counter`
3. `counter++`
4. Print `counter`
5. `counter--`
6. Print `counter`
   </detail>
</details>

**Forventet Output:**
```
10
11
10
```

---

### Opgave 10: All compound operators
**Opgave:**

Erklær en variable for et tal (fx. 10).  
Læg 5 til ved at bruge += og udskriv.  
Træk 3 fra ved at bruge -= og udskriv.  
Øg med 1 ved at bruge ++ og udskriv.  
Mindsk med 1 ved at bruge -- og udskriv.

<details>
<summary>Hjælp</summary>
<detail>

1. Erklær int `number = 10`
2. `number += 5`, print `number`
3. `number -= 3`, print `number`
4. `number++`, print `number`
5. `number--`, print `number`
   </detail>
</details>

**Forventet Output:**
```
15
12
13
12
```



---


### Opgave 11: E-commerce product
**Scenario:** Product information system

**Opgave:**
Erklær og initialiser variable med GODE navne til:

| <!-- --> | Værdi | Dit variabelnavn og værdi |
|----------|-------|---------------------------|
| Product name | "Laptop" | <input type="text" size="35"> |
| Product price | 7999.99 | <input type="text" size="35"> |
| In stock | true | <input type="text" size="35"> |
| Stock quantity | 15 | <input type="text" size="35"> |
| Discount percent | 10.0 | <input type="text" size="35"> |
| Category | "Electronics" | <input type="text" size="35"> |

<details>
<summary>Se svar</summary>

```java
String productName = "Laptop";
double productPrice = 7999.99;
boolean inStock = true;
int stockQuantity = 15;
double discountPercent = 10.0;
String category = "Electronics";
```
</details>

---

### Opgave 12: Student grade system
**Scenario:** Track student grades

**Opgave:**
Erklær og initialiser variable med GODE navne til:

| <!-- --> | Værdi | Dit variabelnavn og værdi |
|----------|-------|---------------------------|
| Student name | "Anna" | <input type="text" size="35"> |
| Test score | 85 | <input type="text" size="35"> |
| Homework score | 92 | <input type="text" size="35"> |
| Final grade (average) | 88.5 | <input type="text" size="35"> |
| Passed course | true | <input type="text" size="35"> |

<details>
<summary>Se svar</summary>

```java
String studentName = "Anna";
int testScore = 85;
int homeworkScore = 92;
double finalGrade = 88.5;
boolean passedCourse = true;
```
</details>

---

### Opgave 13: Booking system
**Scenario:** Hotel room booking

**Opgave:**
Erklær og initialiser variable med GODE navne til:

| <!-- --> | Værdi | Dit variabelnavn og værdi |
|----------|-------|---------------------------|
| Guest name | "Peter Hansen" | <input type="text" size="35"> |
| Room number | 204 | <input type="text" size="35"> |
| Number of nights | 3 | <input type="text" size="35"> |
| Price per night | 899.00 | <input type="text" size="35"> |
| Has breakfast | true | <input type="text" size="35"> |
| Total cost | 2697.00 | <input type="text" size="35"> |

<details>
<summary>Se svar</summary>

```java
String guestName = "Peter Hansen";
int roomNumber = 204;
int numberOfNights = 3;
double pricePerNight = 899.00;
boolean hasBreakfast = true;
double totalCost = 2697.00;
```
</details>

---

### Opgave 14: Fitness tracker
**Scenario:** Daily activity tracking

**Opgave:**
Erklær og initialiser variable med GODE navne til:

| <!-- --> | Værdi | Dit variabelnavn og værdi |
|----------|-------|---------------------------|
| Steps walked today | 8547 | <input type="text" size="35"> |
| Goal steps | 10000 | <input type="text" size="35"> |
| Distance in km | 6.2 | <input type="text" size="35"> |
| Calories burned | 420 | <input type="text" size="35"> |
| Goal reached | false | <input type="text" size="35"> |

<details>
<summary>Se svar</summary>

```java
int stepsToday = 8547;
int goalSteps = 10000;
double distanceKm = 6.2;
int caloriesBurned = 420;
boolean goalReached = false;
```
</details>

---

### Opgave 15: Complete naming exercise
**Scenario:** Library system - track book information

**Opgave:**
Erklær variable med PERFEKTE navne til at gemme:

| <!-- --> | Dit variabelnavn |
|----------|------------------|
| Book title | <input type="text" size="35"> |
| Author name | <input type="text" size="35"> |
| ISBN number | <input type="text" size="35"> |
| Number of pages | <input type="text" size="35"> |
| Is available for borrowing | <input type="text" size="35"> |
| Current borrower (if any) | <input type="text" size="35"> |
| Due date | <input type="text" size="35"> |
| Fine amount if overdue | <input type="text" size="35"> |
| Is bestseller | <input type="text" size="35"> |
| Rating (0.0-5.0) | <input type="text" size="35"> |

Fokuser på at vælge de BEDST mulige navne!

<details>
<summary>Se svar</summary>

```java
String bookTitle = "Java Programming";
String authorName = "John Smith";
String isbn = "978-0-123456-78-9";
int numberOfPages = 456;
boolean isAvailable = true;
String currentBorrower = "";
String dueDate = "2026-02-01";
double fineAmount = 0.0;
boolean isBestseller = true;
double rating = 4.5;
```
</details>

---

Kig på første iteration af [SP1 opgaven](https://1sem.kursusmaterialer.dk/projects/SP1/)


## Refleksionsspørgsmål

Efter du har løst opgaverne, tænk over:
1. Hvad er forskellen mellem int division og double division?
2. Hvornår skal du bruge parenteser i calculations?
3. Hvad giver modulo (%) operator dig?
4. Hvordan kombinerer du strings og numbers?
5. Hvad sker der hvis du skriver "5" + 3 vs 5 + 3?
6. Hvorfor er += mere praktisk end = ... + ?
7. Hvordan tvinger du decimal division med int variables?
