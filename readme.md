## Lav variable til Real-World Scenarios

**Opgave:**
1. Start en nyt projekt. 
2. Opret en folder med navnet 'src' i projektet
3. Lav en klasse i src folderen. Du bestemmer navnet på klassen.
4. Skriv en main metode i klassen.

I det følgende skriver du al din kode i main metoden.


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

Løs første iteration af [SP1 opgaven](https://1sem.kursusmaterialer.dk/projects/SP1/)


## Refleksionsspørgsmål

Efter du har løst opgaverne, tænk over:
1. Hvad er forskellen mellem int division og double division?
2. Hvornår skal du bruge parenteser i calculations?
3. Hvad giver modulo (%) operator dig?
4. Hvordan kombinerer du strings og numbers?
5. Hvad sker der hvis du skriver "5" + 3 vs 5 + 3?
6. Hvorfor er += mere praktisk end = ... + ?
7. Hvordan tvinger du decimal division med int variables?
