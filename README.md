Web scraping creado en Python

Analiza las paginas 

1. #### www.eluniversal.com.mx

2. #### www.elpais.com



```
news_sites:
  eluniversal:
    url: http://www.eluniversal.com.mx
    queries:
      homepage_article_links: '.field-content a'
      article_body: '.field-name-body'
      article_title: '.pane-content h1'
 elpais:
    url: https://elpais.com
    queries:
      homepage_article_links: '.articulo-titulo a'
      article_body: '.articulo-cuerpo'
      article_title: '.articulo-titulo' 
```



Una vez finalizado el proceso de Scraping los guarda en formato .csv para poder ser analizados con Pandas o otro tipo de libreria

Licencia MIT

