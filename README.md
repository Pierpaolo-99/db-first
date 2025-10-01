# Database Auto 

Modellare la struttura di una tabella per memorizzare tutti i dati riguardanti delle auto usate messe in vendita da un concessionario.

## Table Name: "Cars"

## Table columns

- id: (BIGINT) - NOT NULL - AUTO_INCREMENT
- brand: VARCHAR(50) - NOT NULL
- model: VARCHAR(50) - NOT NULL
- version: VARCHAR(50) - NULL
- photo_url: VARCHAR(255) - NULL
- price: DECIMAL(6,3) - NOT NULL
- year: DATE - NOT NULL
- mileage: (MEDIUMINT) - NULL
- location: VARCHAR(100) - NULL
- fuel_type: VARCHAR(20) - NOT NULL
- trasmission: VARCHAR(20) - NOT NULL
- engine_power_kw: (SMALL) - NULL
- engine_power_hp: (SMALL) - NULL
- color: VARCHAR(30) - NULL
- condition: VARCHAR(20) - NULL
- license_plate: VARCHAR(20) - UNIQUE - NOT NULL
- is_available: (TINYINT) - DEFAULT(1)
- description: TEXT() - NULL
- body_type: VARCHAR(30) - NULL 
- vehicle_type: VARCHAR(20) - NULL 
- traction: VARCHAR(10) - NULL
- seats: TINYINT - NULL 
- doors: TINYINT - NULL 
