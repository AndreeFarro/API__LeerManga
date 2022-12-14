# 馃摉 Api LeerManga (Version 1.0.0)
La API se dedic贸 a la obtenci贸n de datos mediante Web scraping a la p谩gina LeerManga.net rastreando su biblioteca, Mangas, Cap铆tulos, 煤ltimos manga agregados, episodios recientes, filtros por g茅nero y paginaci贸n.

Formatos **JSON**.

## Deploy en Vercel y Documentacion
* [api-leermanga.vercel.app](https://api-leermanga.vercel.app/)

## Instalaci贸n de dependencias y run del proyecto

### Clonaci贸n del Repositorio
```shell
git clone https://github.com/AndreeFarro/API__LeerManga
```

### Instalaci贸n de Dependencias
```shell
npm install
```

### Run
El script `build` compila el proyecto en el directorio `./dist` mientras que `start` inicia la aplicacion
```shell
npm run build
npm run start
```
Se dispone de otros scripts que funcionan detras de estos como:
#### copy-files
copia archivos estaticos como HTML, CSS y JS que no estan al alcance de `tsc` ya que este solo compila archivos `*ts`
```shell
npm run copy-files
```
#### clean
limpia el directorio `./dist`
```shell
npm run clean
```
#### dev
iniciar la aplicacion con `nodemon`
```shell
npm run dev
```

---

### Logs
```shell
app listening on port 3000!
version 1 Docs http://localhost:3000
```
### URL: 
- `http://127.0.0.1:3000`

