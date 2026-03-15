# 📘 Fundamentos da Sintaxe do PHP

Este repositório apresenta os **conceitos fundamentais da sintaxe da linguagem PHP**, abordando estruturas básicas utilizadas no desenvolvimento web backend.

PHP é uma linguagem amplamente utilizada para **desenvolvimento de aplicações web no lado do servidor**, permitindo interação com bancos de dados, formulários e APIs.

---
# 📑 Sumário

- Tags PHP
    
- Estrutura de instruções
    
- Variáveis
    
- Tipos de dados
    
- Operadores
    
- Estruturas condicionais
    
- Estruturas de repetição
    
- Arrays
    
- Funções
    
- Inclusão de arquivos
    
- Superglobais
    
- Comentários
---

# 🧩 1. Tags de abertura e fechamento

O código PHP deve estar dentro de **tags específicas**.

``` PHP
<? php  
  echo "Olá Mundo";  
?>
```

- `<?php` → inicia o código PHP
- `?>` → finaliza o código PHP
---

# 📌 2. Instruções e ponto e vírgula

Cada instrução termina com **ponto e vírgula (`;`)**.

``` PHP
<? php  
  echo "Olá";  
  echo "Mundo";  
?>
```

---
# 🧠 3. Variáveis

Variáveis em PHP começam com **$** e possuem **tipagem dinâmica**.
``` php
<? php  

$nome = "Maria";  
$idade = 20;  
  
echo $nome;  
echo $idade;  
  
?>
```
---
# 🗂 4. Tipos de dados básicos

``` php
<?php    
$texto = "Olá";     
$numero = 10;       
$decimal = 5.5;     
$ativo = true;      
$lista = [1,2,3];   
?>
```

Principais tipos:

- `string`
- `int`
- `float`
- `boolean`
- `array`    
---
# ➕ 5. Operadores

## Operadores Aritméticos

| Operador | Descrição     |
| -------- | ------------- |
| +        | Soma          |
| -        | Subtração     |
| *        | Multiplicação |
| /        | Divisão       |
| %        | Resto         |

Exemplo:
``` PHP
$a = 10;  
$b = 5;  
  
echo $a + $b;
```
---
## Operadores de Comparação

| Operador | Descrição      |
| -------- | -------------- |
| ==       | Igual          |
| ===      | Idêntico       |
| !=       | Diferente      |
| >        | Maior          |
| <        | Menor          |
| >=       | Maior ou igual |
| <=       | Menor ou igual |

---
## Operadores Lógicos

| Operador | Descrição |
| -------- | --------- |
| &&       | E         |
| \|       | OU        |
| !        | NÃO       |

---
# 🔀 6. Estruturas Condicionais

## If

``` PHP
<? php  
$idade = 18;  
  
if ($idade >= 18) {  
    echo "Maior de idade";  
}  
?>
```

---
## If / Else

``` php
if ($idade >= 18) {  
    echo "Adulto";  
} else {  
    echo "Menor";  
}
```
---
## Switch

``` php
$dia = 1;  
  
switch ($dia) {  
  
    case 1:  
        echo "Domingo";  
        break;  
  
    case 2:  
        echo "Segunda";  
        break;  
}
```
---

# 🔁 7. Estruturas de Repetição

## While
``` php
$i = 1;  
  
while ($i <= 5) {  
    echo $i;  
    $i++;  
}
```
---
## For

``` php
for ($i = 0; $i < 5; $i++) {  
    echo $i;  
}
```
---
## Foreach

Usado principalmente com arrays.
``` php
$nomes = ["Ana", "Pedro", "Maria"];  
  
foreach ($nomes as $nome) {  
    echo $nome;  
}
```
---
# 📦 8. Arrays

## Array simples
``` php
$frutas = ["Maçã", "Banana", "Laranja"];  
  
echo $frutas[0];
```
---
## Array associativo
``` php 
$pessoa = [  
    "nome" => "João",  
    "idade" => 25  
];  
  
echo $pessoa["nome"];
```
---
# ⚙️ 9. Funções

Funções permitem reutilizar código.
``` PHP
function soma($a, $b) {  
    return $a + $b;  
}  
  
$resultado = soma(5,3);  
  
echo $resultado;
```
---
# 📂 10. Inclusão de arquivos

Permite reutilizar código em vários arquivos.
``` PHP
include "config.php";

ou

require "config.php";
```
Diferença:

- **include** → gera aviso se não encontrar o arquivo
    
- **require** → gera erro fatal
---
# 🌐 11. Superglobais

Variáveis globais disponíveis em qualquer parte do código.

Principais:

- `$_GET`
    
- `$_POST`
    
- `$_SESSION`
    
- `$_COOKIE`
    
- `$_SERVER`

Exemplo:
``` PHP
$nome = $_POST['nome'];  
  
echo $nome;
```
---
# 💬 12. Comentários

Comentários ajudam a documentar o código.

// Comentário de uma linha  
  
# Comentário de uma linha  
``` README
/*  
Comentário  
de várias  
linhas  
*/
```
---
# 🎯 Conclusão
```
Dominar os **fundamentos da sintaxe do PHP** é essencial para desenvolver aplicações web robustas e escaláveis.

Com esses conceitos é possível:

- Criar aplicações web
    
- Manipular formulários
    
- Trabalhar com bancos de dados
    
- Desenvolver APIs
    
- Construir sistemas completos
```
