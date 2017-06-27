# Perceptron
Código para un perceptrón simple con múltiples entradas.  Explicación en los comentarios

Utilización
1. Crear el objeto Perceptron, e.g. perceptron p1(number of inputs)
2. Randomizar entradas weights,  p1.randomize();
3. En el código loop de Arduino actualizar entradas e.g. p1.inputs[0] = analogRead...; p1.inputs[2] = analogRead...
4. Hacer que el perceptron "prediha" e.g. float guess = p1.feedForward();
5. Entrenar si el perceptrón se equivocó e.g. p1.train(desired, obtained);

Librería creada para efectos de enseñanza www.funcostarica.org, bajo licencia GNU
