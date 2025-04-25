
# Estrutura basica de php
<?php
?>

# Echo = print 
# $nome = variavel
# include/require = requisição de outra pasta

<?php
include 'public\amoeba.php';
echo $nome;

?>

# Variaveis

# String

    Qualquer tipo de texto ou simbolo
# Numbers - integers; float(double)

    Qualquer tipo de numero
# Booleans

    True or False; Truthy or Falsy
# Arrays

    Lista de variaveis ex:(['Hallana', 12]);
# Object

    class person
    {

    }
# Null
    Retorna Nulo

# Constantes
    Variavel constante que não pode se alterar o valor ex:

define('NAME', 'Hallana');
echo NAME;

# Constante magica

<?php
function teste()
{
    echo __FUNCTION__;
    echo __METHOD__;
}
teste();
?>

# lista constantes

<?php
$cons = get_defined_constants(true);
var_dump($cons);

?>

#


