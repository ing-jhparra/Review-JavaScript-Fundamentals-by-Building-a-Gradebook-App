El siguiente miniproyecto del curso [JavaScript Algorithms and Data Structures](https://www.freecodecamp.org/learn/javascript-algorithms-and-data-structures-v8/) en FreeCodeCamp es para optar por un cupo en el curso : 

### Aprende ethereum de la mano de Ethkipu & Henry

El miniproyecto

## Review JavaScript Fundamentals by Building a Gradebook App.

A teacher has finished grading their students' tests and needs your help to calculate the average score for the class.

Complete the getAverage function which takes in an array of test scores and returns the average score.

The average is calculated by adding up all the scores and dividing by the total number of scores.
Example Code

### average = sum of all scores / total number of scores

A couple of function calls have been provided for you so you can test out your code.

## Tips

    You can use a loop to iterate over the scores array and add up all the scores.
    You can use the length property to get the total number of scores.

## La funcion principal

```javascript
function getAverage(scores) {
    // Calculate the sum of all scores using a for loop
    let sum = 0;
    for (let i = 0; i < scores.length; i++) {
        sum = sum + scores[i];
    }
    
    // Divide by the number of scores to get the average
    return sum / scores.length;
}
```

### Test 1

```javascript
function calcularPromedio1() {
            const notas1 = [92, 88, 12, 77, 57, 100, 67, 38, 97, 89];
            const promedio = getAverage(notas1);
            document.getElementById('resultado1').textContent = `Promedio: ${promedio.toFixed(2)}`;
}
```

### Test 2

```javascript
function calcularPromedio2() {
            const notas2 = [45, 87, 98, 100, 86, 94, 67, 88, 94, 95];
            const promedio = getAverage(notas2);
            document.getElementById('resultado2').textContent = `Promedio: ${promedio.toFixed(2)}`;
}
```

La función JavaScript forma parte de una página HTML donde se muestra  el cálculo del promedio de calificaciones. La página incluye dos ejemplos prácticos de su ejecución con diferentes conjuntos de datos. El ejercicio puede verlo dando clic [aquí](https://promedios.pages.dev/) y en este repositorio se encuentra incluido el codigo en inde.html.


| [<img src="https://avatars.githubusercontent.com/u/123877201?v=4" width=115><br><sub>Jesus H. Parra B.</sub>](https://github.com/ing-jhparra)
| :---: |