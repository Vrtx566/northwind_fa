
generar un modelo estrella que cuente con 5 dimensiones y una tabla
de hechos de la siguiente manera:
<img width="2048" height="3426" alt="image" src="https://github.com/user-attachments/assets/a612d521-c99b-41f9-85f9-ad25d5f20422" />


- Tabla de hechos que contenga el número de orden (order), el costo de la movilización
(freight), el precio unitario (unit_price), la cantidad de productos (quantity), el valor de
descuento (discount) y el monto de ventas (amount: columna calculada entre cantidad de
productos y precio unitario)
- Tabla de dimensión categorías que cuente con un id de categoría (category_id), el nombre
de la categoría (category_name) y la descripción de la categoría de productos (description).
- Tabla de dimensión clientes que cuente con un id (customer_id) y los campos nombre del
cliente (company_name), nombre del contacto (contact_name), ciudad (city) y región
(región).
- Tabla de dimensión de productos que cuente con un id (producto_id), el nombre del
producto (producto_name), el precio unitario (unit_price) y si está o no descontinuado
(discontinued).
- Tabla de dimensión proveedor que cuente con un id (supplier_id), el nombre del proveedor
(company_name), el nombre del contacto (contact_name), la ciudad (city) y la región
(región).
- Tabla de dimensión tiempo cuyo id es una fecha (order_date) y que tenga los campos mes,
día, año, nombre del mes, nombre del día y trimestre.

<img width="1313" height="1135" alt="image" src="https://github.com/user-attachments/assets/a61627c1-0fc8-4377-87f4-197e58a9047e" />


