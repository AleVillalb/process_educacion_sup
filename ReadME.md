## PASO 1: redirigirte a l acarpeta del proyecto

## PASO 2: cree el ambiente virtual
python -m venv myenv

##PASO 3: activar el entorno virtual
myenv\Scripts\activate

### OBSERVACION: si esta en linux o macOs debe usar:
source myenv\bin\activate

## PASO 4: instalar las librerias del archivo requirements.txt
pip install -r requirements.txt

## PASO 5: luego de descargar el csv mas reciente de la siguiente url
https://datosabiertos.mineduc.cl/titulados-en-educacion-superior/

## PASO 6: ejecutar la aplicacion 
python get_excel_resumen_es.py