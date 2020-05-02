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











  



