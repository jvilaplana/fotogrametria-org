# AFPA

Lloc web de l'Associació de Fotogrametria Patrimonial i Ambiental (AFPA), una entitat sense ànim de lucre dedicada a la documentació i preservació digital del patrimoni i el medi ambient.

El web és estàtic: està fet amb HTML i CSS i no necessita dependències ni cap procés de compilació.

## Contingut

- `index.html`: pàgina principal, projectes i informació de l'associació.
- `alta-soci.html`: informació per fer-se soci o sòcia.
- `codi-conducta.html`: codi de conducta.
- `avis-legal.html` i `privacitat.html`: informació legal i política de privacitat.
- `404.html`: pàgina per a adreces que no existeixen.
- `style.css` i `images/`: estils i recursos gràfics.

## Provar-lo localment

Des de la carpeta del projecte, inicia un servidor HTTP:

```sh
python3 -m http.server 8000
```

Després obre <http://localhost:8000> al navegador.

## Publicació

El fitxer `CNAME` configura el domini personalitzat `fotogrametria.org` per a GitHub Pages. La font de publicació de GitHub Pages s'ha de configurar a les opcions del repositori; un cop publicat, el lloc és accessible a <https://fotogrametria.org>.