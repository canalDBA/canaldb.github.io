# CanalDBA

Este sitio se basó en el template _Naringu_, pero potencialmente no está quedando nada. Estaba algo harcodeado así que le pusimos un poco de amor.

## Introducción


```
sudo gem install jekyll
sudo gem install bower
```

Desde el home de la página:

```
bundle install 
```


Para levantar local:

```
bundle exec jekyll serve --watch --config _config.dev.yml
```

Para producción usar el `_config.yml` o sobreescribir con `_config.prod.yml`
(baseurl es distinto)

### Como trabajar en un branch aparte

Cualquiera que quiera hacer modificaciones tiene que pedir perms para agregarlo al
repo. Preguntar a Emanuel, Iván o Fipar.



```
git checkout -b <nombre_de_tu_feature>
<codeo como un campeón>
git add --all # depende si tenés que agregar cosas
git commit -a -m "...<nombre_de_tu_feature> sarasa" # Más cómodo
git push -u origin <nombre_de_tu_feature>
<revision de peers>
<fixes a lo loco>
git pull  # si peers modificaron
git commit -a # si agregaste algo
git push -u origin <nombre_de_tu_feature>
# Hacé el pull request a master 
```

### Tengo un artículo pero no quiero hacer el push

Escribilo en Markdown, seguí el formato en [posts](https://raw.githubusercontent.com/canalDBA/canaldba.github.io/master/_posts/2017-10-30-el-primer-post.md).


## TODO

## Slack

Para solicitar el link, tiene que contactarnos por tuiter o mail.

## IRC

Soon.

## Twiter

La cuenta la maneja el que quiere, pedir creds a Iván o Emanuel.

## Disqus

Falta setear disqus.



### Template author
**Rizky Ariestiyansyah**
**Gildásio Júnior** 
### License
Open sourced under the [MIT license](LICENSE.md).
