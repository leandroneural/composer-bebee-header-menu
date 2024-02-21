# BeBee Test
## Esta é uma marcação para teste de aplicativo composer para API BeBee

[![N|Solid](https://neuralbrain.nyc3.digitaloceanspaces.com/general/logo_bebee.png)](https://www.bebee.com.br)


Esta aplicação é apenas um exemplo para testes de criação de biblitecas para aplicações BeBee

## Instalação

Para instalar execute o comando abaixo:

```shell
 composer require bebee/bebee-header-menu
 ```


## Exemplo 
```php
 <?php
 
    require __DIR__ . '/../vendor/autoload.php';
    
    
    use BeBee\BeBeeHeaderMenu\TestMenu;
    
    $testMenu = new TestMenu();
    
    $response = $testMenu->test("OLA MUNDO");
    
    echo $response . PHP_EOL;
 
 
 ```
