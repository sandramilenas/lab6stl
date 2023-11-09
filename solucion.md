SELECT *
FROM Cities
INNER JOIN Concentrations USING(city)
ORDER BY 	Cities ."Total Population" DESC 
LIMIT 10;

SELECT *
FROM Cities
INNER JOIN Concentrations USING(city)
ORDER BY 	Cities ."Total Population" ASC 
LIMIT 10;

SELECT *
FROM Cities
INNER JOIN Concentrations USING(city)
ORDER BY 	Concentrations ."overall_aqi" DESC 
LIMIT 10; 
Estos fueron los querys que se utilizaron en el laboratporio como fueron solucitados para los analisis de datos.

se puso analizar no se encuentra una relacion entre la poblacion y la calidad del aire,dado en que las ciudades con mucha poblacion la calidad del aire no era tan mala.
En cambio se encontro que las cuidades con peor calidad de aire no superaba mas 200.000 habitantes.
se tendria que validar otros datos como la industria cerca a lass ciudades,condiciones climatologicas y geograficas.