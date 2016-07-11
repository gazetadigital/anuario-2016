#Anuário 2016 - A Gazeta

##Imagens

As imagens ao longo do texto podem ter 3 tamanhos diferentes. O código é o mesmo, apenas trocando o tamanho no local indicado.

Salve as imagens na pasta `images/photos` e insira no código o nome das mesmas, com a extensão.

Também é possível exibir legenda ou créditos para o fotógrafo. Caso um desses dois seja necessário, use o código **Com legenda* abaixo. Caso apenas um dos dois elementos seja necessário, a linha inteira do outro pode ser apagada.

**_Itens editáveis:_**

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

`TAMANHO_DA_IMAGEM`: **small**

<img src="/samples/imagem_small.png" width="400"/>

<hr/>

`TAMANHO_DA_IMAGEM`: **medium**

<img src="/samples/imagem_medium.png" width="400"/>

<hr/>

`TAMANHO_DA_IMAGEM`: **big**

<img src="/samples/imagem_big.png" width="600"/>

<hr/>

##Citações



