# online-shoppers-purchasing-intention

## Contenido
- `online_shoppers_analysis.ipynb`: notebook con el análisis.
- `dataset/online_shoppers.csv`: datos usados en el notebook.

## Instrucciones

1) Clonar el repositorio

	- Desde la terminal:
	  ```powershell
	  git clone https://github.com/Nicolas-carmona16/online-shoppers-purchasing-intention.git
	  cd online-shoppers-purchasing-intention
	  ```

2) Abrir en VS Code (u otro editor que soporte notebooks)

	- Asegúrate de tener la extensión de Jupyter instalada en VS Code para ejecutar notebooks.

3) Dependencias

	- La primera celda del notebook ya instala lo necesario, simplemente ejecútala. Esta contiene:
	  ```python
	  %pip install ucimlrepo matplotlib seaborn pandas
	  ```
	- Esta celda instala paquetes.

4) Ejecutar el notebook

	- Abre `online_shoppers_analysis.ipynb` y ejecuta las celdas en orden.

5) Datos

	- El dataset está en `dataset/online_shoppers.csv`. No es necesario descargar nada extra.


## Opción: Google Colab (sin configuraciones extras)

1) Sube el notebook a Google Colab.

2) Colab ejecuta la primera celda sin pasos previos, solo ejecútala y continúa con el resto de las celdas.
```python 
%pip install ucimlrepo matplotlib seaborn pandas
```

3) No se necesita configurar entornos ni kernels en Colab.