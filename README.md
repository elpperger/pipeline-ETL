# Pipeline ETL em Python

### Pipeline que utiliza o ID de 10 clientes do banco XPTO, contidos em uma planilha de excel, que avalia o gasto do cartão de crédito de 6 meses de cada um dos clientes, caso o valor gasto mensal seja menor que R$ 1000.00, uma mensagem é enviada por email de promoções de lojas de produtos parceiras do banco.

#### Tecnologias utilizadas
* pandas
* random
* smtplib
* openpyxl
* email.message
* SMTP

#### Tutorial de como habilitar o Gmail para enviar e-mail por aplicativos externos. Dica retirada da galera do GestãoPro:

Segue o link: https://gestaopro.com.br/manual-sistema-gestaopro-post/como-habilitar-o-gmail-para-enviar-e-mail-por-aplicativos-externos

**OBS.:** No passo número 11 do tutorial acima, a opção "Senhas de app" está dentro da opção "Verificação em duas etapas", ao contrário que o demonstrado no tutorial.
