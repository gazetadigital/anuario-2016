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
<br/><br/>

`TAMANHO_DA_IMAGEM`: **small**
<br/><br/>

<img src="/samples/imagem_small.png" width="400"/>

<br/><hr/><br/>

`TAMANHO_DA_IMAGEM`: **medium**
<br/><br/>

<img src="/samples/imagem_medium.png" width="400"/>

<br/><hr/><br/>

`TAMANHO_DA_IMAGEM`: **big**
<br/><br/>

<img src="/samples/imagem_big.png" width="600"/>

<br/><hr/><br/>

##Citações

As citações podem ser apresentadas em 2 formatos, ambos com ou sem informações da pessoa citada. Um dos formatos é de citação curta, na coluna lateral (fora do texto). E outro é para citações maiores, e fica no meio dos parágrafos.

`TEXTO_DA_CITAÇÃO` é autoexplicativo. **Não inserir as aspas (estas serão exibidas automaticamente).**

`FOTO_DA_PESSOA` inserir nome da imagem salva na pasta, **com a extensão** (.jpg ou .png, por exemplo).

`NOME_DA_PESSOA` é autoexplicativo.

`CARGO_OU_OUTRA_DESCRIÇÃO` é destinado, como esperado para informar o cargo, ou alguma outra informação curta sobre o autor.

Os itens `FOTO_DA_PESSOA` e `CARGO_OU_OUTRA_DESCRIÇÃO` são opcionais quando utilizando o modelo *com autor*. Caso não deseje usar um deles, remova a linha inteira do item.

#####Alternando formato de exibição

Para que a citação fique no meio do texto (e não deslocada para a lateral), retire a palavra *aside* de `class="aside quote"`, ficando assim: `<figure class="quote">`.

#####Com autor
```
<figure class="aside quote">
  <blockquote>TEXTO_DA_CITAÇÃO</blockquote>
  <figcaption>
    <img src="images/photos/FOTO_DA_PESSOA" alt="">
    <p class="name">NOME_DA_PESSOA</p>
    <p class="desc">CARGO_OU_OUTRA_DESCRIÇÃO</p>
  </figcaption>
</figure>
```

#####Sem autor
```
<figure class="aside quote">
  <blockquote>TEXTO_DA_CITAÇÃO</blockquote>
</figure>
```

####Exemplos
<br/><br/>

Lateral `<figure class="aside quote">`
<br/><br/>

<img src="/samples/citacao_aside.png" width="350"/>

<br/><hr/><br/>

Texto `<figure class="quote">`
<br/><br/>

<img src="/samples/citacao_texto.png" width="500"/>

<br/><hr/><br/>

##Números

Informações numéricas/estatísticas podem ser inseridas em posição lateral ao texto, com as seguintes características:

`NÚMERO` Número desejado (ex.: 80,8)

`DIMENSÃO` Dimensão do número utilizado (ex.: Bilhões de Reais)

`TEXTO_COMPLEMENTAR` Texto complementar que possa acompanhar o número. Caso não seja necessário, remova a linha inteira do item.

```
<figure class="aside numbers">
  <p><span class="number">NÚMERO</span><br /><strong>DIMENSÃO</strong></p>
  <figcaption>TEXTO_COMPLEMENTAR</figcaption>
</figure>
```

####Exemplo
<br/><br/>

<img src="/samples/numeros.png" width="350"/>

<br/><hr/><br/>
