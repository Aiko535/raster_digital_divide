# Territorial Digital Divide — Cusco, Peru

## Research Question
How does the spatial distribution of mobile connectivity compare to urbanization levels across the Cusco region, and where are the most digitally excluded territories?

## Dependencies
pip install -r requirements.txt

## How to Run
1. Place VNL_cusco_2025.tif and kernel_cobmovil2019_50m.tif in the data/ folder
2. Open notebooks/digital_divide_cusco.ipynb in Jupyter
3. Run all cells in order

## Output Files
- vnl_norm.tif: Normalized nighttime lights raster
- conn_norm.tif: Normalized connectivity raster
- ibd_brecha_digital.tif: Digital Divide Index [-1,1]
- clasificacion_brecha.tif: 4-class territorial classification
- dashboard_brecha_digital.png: Composite figure of all maps

## Findings
The city of Cusco and secondary urban centers show high nighttime radiance but uneven mobile coverage, revealing an active digital divide in peri-urban zones. Large rural areas exhibit both low light and low connectivity, representing maximum digital exclusion. The Critical Divide class dominates the regional landscape, underscoring the need for targeted infrastructure investment.
