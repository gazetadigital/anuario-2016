#Anuário 2016 - A Gazeta

##Imagens

`TAMANHO_DA_IMAGEM` pode ser: `small` | `medium` | `big`

`NOME_DA_IMAGEM` inserir nome da imagem salva na pasta, **com a extensão** (.jpg ou .png, por exemplo).

`LEGENDA` e `FOTÓGRAFO` são opcionais. Caso a imagem possua apenas um dos dois, apague a linha inteira do item desnecessário.


#####Sem legenda
```
<figure class="media" data-size="TAMANHO_DA_IMAGEM">
  <img src="/images/photos/NOME_DA_IMAGEM" alt="">
</figure>
```

#####Com legenda
```
<figure class="media" data-size="TAMANHO_DA_IMAGEM">
  <img src="/images/photos/NOME_DA_IMAGEM" alt="">
  <figcaption>
    <div class="description">LEGENDA</div>
    <div class="credit">Foto: FOTÓGRAFO</div>
  </figcaption>
</figure>
```

####Exemplos



