# Rotina paga gerar arquivo(s)
`topojson ../shapefile/Munic.shp -o municipio.json --id-property=+GEOCODIGO --p name=NOME,uf=UF,codigo=+GEOCODIGO,regiao=REGIAO,meso=MESOREGIAO,micro=MICROREGIA`