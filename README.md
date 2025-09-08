## 1. Actividad Grupal 1 – Crecimiento de un tumor  

### 1.1 Modelo de Gompertz  

El modelo de Gompertz describe el crecimiento de un tumor de la forma:  

$$
\frac{dN}{dt} = rN \ln\left(\frac{K}{N}\right)
$$  

donde:  
- $N(t)$: tamaño del tumor.  
- $r$: tasa de crecimiento inicial.  
- $K$: capacidad de carga (tamaño máximo alcanzable).  

---

## 2. Enunciados de la tarea  

### 2.1 Ítem 1 (1 pto)  
Mostrar que la ecuación anterior puede escribirse como:  

$$
\frac{dN}{dt} = N \,(a - b \ln N)
$$  

Sugerencia: definir $K = e^{a/b}$.  

---

### 2.2 Ítem 2
Determinar la **solución general** de la ecuación diferencial.  

---

### 2.3 Ítem 3 
Dada la condición inicial $N(0) = N_0$, determinar la **solución particular**.  

---

### 2.4 Ítem 4 
Analizar el **comportamiento asintótico** del tumor cuando $t \to \infty$ e interpretar el resultado.  

---

### 2.5 Ítem 5
Suponiendo que una **terapia** reduce la tasa de crecimiento del tumor:  
- Después de un tiempo $t_0$ se aplica la terapia.  
- La nueva tasa es $r'$ con $r' < r$.  

Encontrar la **nueva solución** para $N(t)$ cuando $t \geq t_0$ y discutir su efecto en la progresión del tumor.  

---

### 2.6 Ítem 6  
Proponer valores para las constantes y:  

1. (**1.5 ptos**) Graficar y comparar la solución **con y sin terapia** para un valor de $t_0$.  
2. (**1.5 ptos**) Graficar y comparar la solución **para tres valores distintos de $t_0$**.  

---

### 2.7 Ítem 7 
Investigar un **método numérico** que resuelva el problema del ítem 1.  
Aplicar el mismo método numérico al caso con terapia (ítem 5).  

---

### 2.8 Ítem 8 
Comparar los resultados **analíticos y numéricos** del ítem 5.  
Describir al menos **tres observaciones importantes**.  

---

### 2.9 Ítem 9  
Resolver la ecuación diferencial del ítem 5 con **uso de IA**.  
Validar la respuesta obtenida con el resultado del ítem 8.  
