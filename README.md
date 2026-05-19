# Tarea2Recu

## Apartado 1
```bash
CREATE TABLE Pokemons (
    idPokemon SERIAL PRIMARY KEY,
    nombre VARCHAR(40) NOT NULL,
    capturado BOOLEAN DEFAULT FALSE,
    tipoPokemon VARCHAR(120),
    numeroPokemon INTEGER,
    fechaCaptura DATE
);

```

![](1.png)

## Apartado 2
```bash
INSERT INTO Pokemons (nombre, capturado, tipoPokemon, numeroPokemon, fechaCaptura) VALUES
('Pikachu', TRUE, 'Eléctrico', 1, '2026-05-15'),
('Charizard', FALSE, 'Fuego / Volador', 2, '2026-05-18'),
('Bulbasaur', TRUE, 'Planta / Veneno', 3, '2026-05-10');

```

![](2.png)

## Apartado 3
```bash
SELECT * FROM Pokemons ORDER BY fechaCaptura DESC;

```

![](3.png)
