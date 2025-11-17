# 🧩 UNIDAD 1

## [↩️ Volver a la portada](index.md)

## 📘 Lógica Proposicional

**¿Qué es una proposición lógica?**
Una proposición lógica es una oración declarativa que siempre tiene un valor de verdad definido: es verdadero (V) o falso (F). No puede ser ambigua ni carecer de valor de verdad. Las proposiciones son los componentes fundamentales de la lógica formal. 

## 🔗 Conectores Lógicos
Los conectores permiten unir proposiciones para formar proposiciones compuestas.

### **1. Negación (¬)**
Invierte el valor de verdad.  
- Si *p* es V → ¬p es F  
- Si *p* es F → ¬p es V  

**Ejemplo:**  
- p: “Hoy es lunes”  
- ¬p: “Hoy no es lunes”

---

### **2. Conjunción (∧)**
Representa el **“y” lógico**.  
Es **verdadera solo cuando ambas proposiciones son verdaderas**.

**Ejemplo:**  
p: Hoy es lunes  
q: Está lloviendo  
p ∧ q: Hoy es lunes **y** está lloviendo

---

### **3. Disyunción (∨)**
Representa el **“o” inclusivo**.  
Es **falsa solo cuando ambas proposiciones son falsas**.

**Ejemplo:**  
p: Hoy es viernes  
q: Estoy contento  
p ∨ q: Hoy es viernes **o** estoy contento

---

### **4. Condicional (→)**
Expresa “**si… entonces…**”.  
Es **falso únicamente** cuando:  
- el antecedente es V  
- el consecuente es F  

**Ejemplo:**  
p → q  
“Si soy electo diputado, entonces disminuiré impuestos.”

---

### **5. Bicondicional (↔)**
Significa **“si y solo si”**.  
Es **verdadero cuando ambos valores coinciden**:  
- V ↔ V  
- F ↔ F

**Ejemplo:**  
“Está lloviendo **si y solo si** la calle está mojada.”

---

## 📊 Tablas de Verdad
Una tabla de verdad permite analizar cómo varía el valor de una proposición compuesta según las combinaciones de V y F de sus proposiciones simples.

### **Pasos para construir una tabla de verdad**
1. **Identificar proposiciones simples** (p, q, r…).  
2. **Calcular el número de filas**: 2ⁿ.  
3. **Crear columnas para las proposiciones simples**.  
4. **Añadir columnas para sub-expresiones** según el orden de los conectores.  
5. **Rellenar valores** usando las reglas de cada conector.  
6. **Evaluar la expresión final** en la última columna.

---

## 🧮 Clasificación de proposiciones
- **Tautología** → siempre verdadera.  
- **Contradicción** → siempre falsa.  
- **Contingencia** → mezcla de valores (a veces V y F).

---

# 🧩 Leyes de las Proposiciones Lógicas

## 🔹 1. **Leyes de Identidad**
- p ∧ V ≡ p  
- p ∨ F ≡ p  
- p ∧ F ≡ F  
- p ∨ V ≡ V  

Estas leyes describen cómo se comporta una proposición al combinarse con los valores Verdadero o Falso.

---

## 🔹 3. **Leyes Idempotentes**
- p ∧ p ≡ p  
- p ∨ p ≡ p  

Repetir la proposición no cambia el resultado.

---

## 🔹 4. **Leyes Conmutativas**
- p ∧ q ≡ q ∧ p  
- p ∨ q ≡ q ∨ p  

El orden no altera el resultado.

---

## 🔹 5. **Leyes Asociativas**
- (p ∧ q) ∧ r ≡ p ∧ (q ∧ r)  
- (p ∨ q) ∨ r ≡ p ∨ (q ∨ r)  

Permiten reagrupar sin cambiar significado.

---

## 🔹 6. **Leyes Distributivas**
- p ∧ (q ∨ r) ≡ (p ∧ q) ∧ (p ∧ r)  
- p ∨ (q ∧ r) ≡ (p ∨ q) ∨ (p ∨ r)  

Muestran cómo se “distribuyen” ∧ y ∨ entre sí.

---

## 🔹 7. **Leyes de De Morgan**
- ¬(p ∧ q) ≡ ¬p ∨ ¬q  
- ¬(p ∨ q) ≡ ¬p ∧ ¬q  

La negación cambia conectores y niega cada término.

---

## 🔹 8. **Ley de Doble Negación**
- ¬(¬p) ≡ p  

---

## 🔹 9. **Leyes de Absorción**
- p ∨ (p ∧ q) ≡ p  
- p ∧ (p ∨ q) ≡ p



# 🧠 Reglas de Inferencia

Las reglas de inferencia permiten derivar conclusiones válidas a partir de premisas. Son la base de las demostraciones lógicas.

## 🔹 1. **Modus Ponens (MP)**
Si p es verdadero y p → q es verdadero, entonces q es verdadero.

Premisas:  
1) p  
2) p → q  
Conclusión:  
∴ q  

---

## 🔹 2. **Modus Tollens (MT)**
Si p → q es verdadero y q es falso, entonces p es falso.

Premisas:  
1) p → q  
2) ¬q  
Conclusión:  
∴ ¬p  

---

## 🔹 3. **Silogismo Hipotético (SH)**
Permite encadenar dos condicionales.

Premisas:  
1) p → q  
2) q → r  
Conclusión:  
∴ p → r  

---

## 🔹 4. **Silogismo Disyuntivo (SD)**
De una disyunción, descartar un término permite afirmar el otro.

Premisas:  
1) p ∨ q  
2) ¬p  
Conclusión:  
∴ q  

---

## 🔹 5. **Dilema Constructivo**
Premisas:  
1) p → r  
2) q → s  
3) p ∨ q  
Conclusión:  
∴ r ∨ s  

---

## 🔹 6. **Dilema Destructivo**
Premisas:  
1) p → r  
2) q → s  
3) ¬r ∨ ¬s  
Conclusión:  
∴ ¬p ∨ ¬q  

---

## 🔹 7. **Simplificación**
De una conjunción se puede obtener cualquier parte.

Premisa: p ∧ q  
Conclusión: ∴ p  

---

## 🔹 8. **Adición**
Si p es verdadero, se puede formar una disyunción verdadera.

Premisa: p  
Conclusión: ∴ p ∨ q  

---

## 🔹 9. **Conjunción**
Si dos proposiciones son verdaderas, se pueden unir.

Premisas:  
1) p  
2) q  
Conclusión:  
∴ p ∧ q  

## 📌 Actividades realizadas

### Aprendizaje en contacto con el docente (ACD)
En la primera actividad (ACD1) se desarrolla una presentación completa sobre los conceptos básicos de la lógica proposicional, incluyendo qué es una proposición lógica, los distintos conectores lógicos (negación, conjunción, disyunción, condicional y bicondicional) y el uso de tablas de verdad para evaluar proposiciones compuestas. 

En la segunda actividad (ACD2) se profundiza en las leyes fundamentales de la lógica proposicional (identidad, idempotencia, negación, doble negación, absorción, etc.) y en las principales reglas de inferencia, como Modus Ponens, Modus Tollens, Silogismo Hipotético, Silogismo Disyuntivo, Adición, Simplificación y Conjunción. 
[ACD1](ACD1.pdf)
<br>
[ACD2](ACD2.pdf)

### Aprendizaje práctico experimental (APE) 
Esta es un actividad grupal enfocada en los conceptos básicos de lógica proposicional como tablas de verdad y conectores lógicos.
[APE1](APE1.pdf)

### Aprendizaje autónomo (AA) 
Esta es un actividad grupal con ejercicios sobre leyes de las preposiciones y reglas de las inferencias.
[AA1](AA1)

