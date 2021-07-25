<center style="background-color:black"><h1>{Nombre completo personaje}</h1></center>

<center>{Imagen del personaje - Sims 4}</center>

```ad-info
title: Identificación básica
- *<ins>Raza</ins>* - {Humano/Híbrido/Arcano/Alltimer} - {Especificación según raza}
- *<ins>Origen</ins>* - {Antaskra/Auros/Ífraust/Uningston/Xinla}
- *<ins>Nivel</ins>* - {1 - 100}
- *<ins>Elemento Natural</ins>* - {Fuego/Agua/Aire/Tierra}
- *<ins>Capacidad Soulstone</ins>* - {Num}
```

```ad-info
title: Identificación concreta
- *<ins>Estado</ins>* - {Vivo/Muerto/Desconocido}
- *<ins>Puesto</ins>* - {Estudiante/Héroe/Director de Héroe/Ciudadano/etc}
- *<ins>Fecha de nacimiento</ins>* - {Fecha} 
- *<ins>Edad</ins>* - {int}
- *<ins>Sexo</ins>* - {Femenino/Masculino0}
- *<ins>Altura</ins>* - {int}
- *<ins>Peso</ins>* - {int}
```

```ad-success
title: Capacidad/Competencia

<center><h3>Raza - Proficiency number</h3></center>

{

*Capacidad/Competencia*
Según el nivel -> [{1,2,3,4} -> +2] [{5,6,7,8} -> +3] [{9,10,11,12} -> +4] [{13,14,15,16} -> +5] [{17,18,19,20} -> +6]

Este número se agrega como bonus a sus características específicas. Obviamente no a todas, sino que se escoje un set concreto de características, set el cual es determinado por la clase/raza/background del que proceda el personaje.

El nivel de la capacidad/competencia aumenta a más que suba de nivel. El sistema de subida de nivel, en DdH, aún no está especificado al 100%, aunque seguramente será modifica según los acontecimientos que vayan surgiendo.

}

```


```ad-example
title: Características generales

{

<center><i>Característica</i> - (Número general) [Modifier]</center>

Números generales - Van de 0 a 15. - La suma de puntos debe ser 75.

Modifiers - $\frac {(\text{Puntos} - 10)}{2} = Modifier$

}

- *Fuerza* - 
- *Destreza* - 
- *Complexión* - 
- *Inteligencia* - 
- *Sabiduría* - 
- *Carisma* - 
```

```ad-example
title: Características específicas

{

Puntos = Características generales + competencia(no en todos, sino en algunos, dependiendo de la clase/raza del personaje)

}

|      Característica      | Puntos |   Característica    | Puntos |
|:------------------------:|:------:|:-------------------:|:------:|
|      Agilidad (Dex)      |        | Intimidación (Cha)  |        |
| Trato con animales (Wis) |        |   Medicina (Wis)    |        |
|    Conocimiento (Int)    |        |  Natulareza (Int)   |        |
|     Atletismo (Str)      |        |  Percepción (Wis)   |        |
|       Engaño (Car)       |        |  Rendimiento (Cha)  |        |
|      Historia (Int)      |        |  Persuasión (Cha)   |        |
|   Interpretación (Wis)   |        |    Sigilo (Des)     |        |
|    Perspicacia (Wis)     |        | Supervivencia (Wis) |        |

```

```ad-abstract
title: Personalidad

{Se describe la personalidad del personaje}
```

```ad-tip
title: Ideales

{Se escriben las "cosas" que motivan al personaje a ser quien es y lo que le motiva a alcanzar sus objetivos}
```

```ad-bug
title: Relaciones/Familia

{Se escribe la familia que posee, amigos, animales de compaía, cosas que pueden influenciar de gran manera (o no) al personaje}
```

```ad-failure
title: Defectos

{Se enlista/describe una serie de características negativas sobre el personaje}
```

```ad-example
title: Armas y Habilidades

{Se expone una lista con sus armas y sus características}
```