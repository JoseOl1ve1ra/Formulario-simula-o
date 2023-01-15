
# Formulário ligado ao banco de dados MySQL
 

# Sobre o projeto 
>Elaboração de ficha de cadastro para simulação de financiamento

![SQL](https://github.com/JoseOl1ve1ra/formulario-simula-o/blob/main/assets/SQL.jpg.jpeg)





>Como executar o projeto:

>MySQL Workbench 
>localhost/formulario/config.php

```

<?php 

$dbHost = 'Localhost';
$dbUsername = 'root';
$dbPassword = '';
$dbdbName = 'formulario-diana';

$conexao = new mysqli($dbHost,$dbUsername,$dbPassword,$dbdbName);

//if($conexao->connect_errno)
// {
  //  echo "Erro";
// }
 //else
// {
 // echo "conexão efetuada com sucesso";
// }

?>  

```

# Tecnologias utilizadas
## Back end
- PHP
- APACHE
- XAMPP

## Front end
- HTML / CSS

## Implantação em produção
- Back end: Heroku
- Front end web: Netlify
- Banco de dados: MySQL


## Back end
Pré-requisitos: PHP 8.1.10


# Autor
José Oliveira

 https://www.linkedin.com/in/jose-ol1ve1ra/    
