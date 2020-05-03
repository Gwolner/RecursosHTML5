# Curso HTML 5

Aperfeiçoamento dos conhecimentos de HTML 5 com o curso da Node Studio Treinamentos

## Estrutura HTML

Definição de HTML 5
```html
<!DOCTYPE html>
```

Definição de linguagem da página
```html
<html lang="pt-br">
```

Uso de caracteres latinos
```html
<meta charset="utf-8">
```

Descrição da página
```html
<meta name="description" content="A perfeiçoando o HTML 5">
```

Agragando palavras chaves
```html
<meta name="keywords" content="HTML, CSS, PHP">
```

Informando o autor
```html
<meta name="author" content="Guilherme Wolner">
```

Recarrega a página a cada n segundos
```html
<meta http-equiv="refresh" content="10">
```

## Corpo do texto

Deixar um conteúdo de texto editável (atributo contenteditable)
```html
<div contenteditable>
  <h1>Título</h1>
  <p>Corpo do texto que será editável</p>
</div>
```

## Tabelas

Título da tabela (dentro da tag table)
```html
<caption>Cadastro de Clientes</caption>
```

Definindo grupo de colunas
```html
<colgroup>
  <col class="nome">
  <col class="idade">
  <col class="email">
</colgroup>
```

Definindo sessões na tabela 
```html
<thead>
  Para o cabeçalho
</thead>

<tbody>
  Para o corpo da tabela
</tbody>

<tfoot>
  Para o rodapé
</tfoot>
```

Mesclando células
```html
<td rowspan="2">Mescladno linhas</td>

<td colspan="3">Mescladno colunas</td>
```

## Lista

Atribuindo sub-listas
```html
<ol type="A">
  <li>Notebook</li>
  <li>Geladeira</li>
  <li>TV
    <ol>
      <li>LED</li>
      <li>OLED</li>
      <li>LCD</li>
    </ol>
  </li>
  <li>Forno</li>
</ol>
```

## Formulário

Adicinando borda/contorno/legenda a um formulário
```html
<fieldset>
  <legend>Título da legenda</legend>
  <form>
    ...
  </form>
</fieldset>
```

Barra de nível
```html
<input type="range" name="quantidade"><br>
```

Definindo uma cor
```html
<input type="color" name="cor"><br>
```

Campos com dados pré-definidos e aceita dados novos 
```html
<input name="cursos" list="lista-cursos">

<datalist id="lista-cursos">
  <option value="HTML 5">
  <option value="CSS">
  <option value="PHP">
</datalist><br>
```

Grupos em caixa de seleção
```html
<select name="veiculo">
  <optgroup label="Carro">
    <option value="ferrari">Ferrari</option>
    <option value="lamborghini">Lamborghini</option>
  </optgroup>
  <optgroup label="Moto">
    <option value="pop100" selected>Pop 100</option>
    <option value="zig50">Zig-50</option>
  </optgroup>
</select><br>
```

Associando um campo externo a um formulário
```html
<form id="form-cadastro" action="destino.php" method="POST">
  Email:<br>
  <input type="email" name="email" required autocomplete="on">
  <input type="submit" name="btn-cadastrar" value="Cadastrar">
</form>

<input type="text" name="usuario" form="form-cadastro" required>
```

Dois botões em um forma para destinos diferentes
```html
<form id="form-cadastro" method="POST">
  <input type="email" name="email" required autocomplete="on">
  <input type="submit" name="btn-cadastrar" formaction="cadastrar.php" value="Cadastrar">
  <input type="submit" name="btn-enviar-email" formaction="enviar-email.php" value="Enviar por email">
</form>
```

Mais de um método de envio (Ex: POST e GET)
```html
<form id="form-cadastro">
  <input type="email" name="email" required autocomplete="on">
  <input type="submit" name="btn-cadastrar" formmethod="GET" formaction="cadastrar.php" value="Cadastrar">
  <input type="submit" name="btn-enviar-email" formmethod="POST" formaction="enviar-email.php" value="Enviar por email">
</form>
```

## Navegação na página

Ordem de nvegação com a tecla TAB (tabindex)
```html
<a href="https://pt.lipsum.com/" tabindex="3" target="_blank">Lorem Ipsum</a>
<a href="https://www.google.com/" tabindex="1" target="_blank">Google</a>
<a href="https://fordev.netlify.app/" tabindex="2" target="_blank">For Dev</a>
```


```html

```


```html

```


```html

```


```html

```


```html

```


```html

```



```html

```








  



