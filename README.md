# doblenetDesktop
# NOTA!
Es necesario tener un servidor directo al microtik para guardad la base de datos MySQL
ademas de ejecutar el script de cortes automaticos

# Requisitos
pip install -r requirements.txt


# Obtener requisitos
pip freeze > requirements.txt

# Importar base de datos al servidor
mysql -h 122.122.126.99 -u dni -p alpha < alpha.sql