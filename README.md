#Organize seu código google app script


A ideia deste projeto é mostrar como organizar de forma satisfatória seus códigos feito no GAS.

Segue o modelo:

1 - Crie uma estrutura seguindo o padrão abaixo:

![ScreenShot](https://googledrive.com/host/0B7QP5NL8v9h6bTY4VEhPdWJzWUk)

2 - Crie arquivos .html para seu html, javascript e css;

3 - Adicione as tags:

< ?!= HtmlService.createHtmlOutputFromFile('Código CSS').getContent();?>

< ?!= HtmlService.createHtmlOutputFromFile('Código Javascript').getContent();?>

O ideal é ficar semelhante a esta estrutura:
```html
'<?!= HtmlService.createHtmlOutputFromFile('Código CSS').getContent(); ?>

<body>
  <div>

  </div>
</body>

'<?!= HtmlService.createHtmlOutputFromFile('Código Javascript').getContent(); ?>
```
Acesse o código completo no GAS [Clicando aqui](https://script.google.com/a/macros/livrorapido.com.br/d/1RQSUC4KQRH6aZvBv-BXxfrjN372pSQZOc2-afkk4Dlf9vwgw3ypPWZyl/edit?template=default&folder=0ALQP5NL8v9h6Uk9PVA&usp=drive_web)

