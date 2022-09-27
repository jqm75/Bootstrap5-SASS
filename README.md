# SPRINT 2 - Bootstrap & SASS.

Construcció d'un web responsive per desktop, tauletes i telèfons. Amb `Bootstrap (no CDN) i SASS (un preprocessador CSS)`.

Per veure bé, el web. S'ha d'executar des d'un IDE, per exemple VSC amb Live Server o des d'un servidor. D'aquesta manera el fitxer JS carregarà bé i és podrà visualitzar correctament el menú i la validació del mail. Això és degut a les polítiques CORS (Cross-Origin Resource Sharing) i he hagut de carregar aquest SCRIPT a l'HTML.

```
<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.2.1/dist/js/bootstrap.bundle.min.js" integrity="sha256-qFsv4wd3fI60fwah7sOZ/L3f6D0lL9IC0+E1gFH88n0=" crossorigin="anonymous"></script>
```
Ja que la següent instrocció **NO** és visualitzava bé fent un *@import* al fitxer de SASS.

```
@import "../node_modules/bootstrap/dist/js/bootstrap.bundle.min.js
```

Més info: 

https://lenguajejs.com/javascript/peticiones-http/cors/

https://stackoverflow.com/questions/52919331/access-to-script-at-from-origin-null-has-been-blocked-by-cors-policy


Aquest recurs l'he trobat seguint aquest fil a Stack Overflow:

https://stackoverflow.com/questions/66919051/bootstrap-js-not-loading-correctly/66920198#66920198



