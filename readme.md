#DB Car

Table name: cars

Table columns:
- id | BIGINT | PK AI NOTNULL UNIQUE
- brand | VARCHAR(20) | NOTNULL
- model | VARCHAR(30) | NULL 
- year | YEAR | NULL 
- engine | VARCHAR(30) | NULL 
- kw | SMALLINT | NULL
- gearbox | VARCHAR(20) | NULL
- km | SMALLINT | NULL
- km/l | TINYINT | NULL
- price | FLOAT(6,2) | NULL
- cover | VARCHAR(255) | NULL
- description | TEXT | NULL


Example
- id = 01
- brand = Renault
- model = Clio
- year = 2019
- engine = Petrol
- kw = 75
- gearbox = Manual
- km = 40000
- km/l = 20km/l
- price = 15000
- cover = https://...
- description = La macchina è tenuta bene e non presenta danni...