
### Composer

```shell
$ composer create-project laraerp/laraerp -s dev
$ php artisan key:generate
```

Acesse o diretório `laraerp` e configure as variáveis do banco de dados no arquivo `.env`. Feito isso, execute os comandos para criar e popular as tabelas:

```shell
$ php artisan migrate
$ php artisan db:seed --class="LaraerpSeeder"
```

# acesso

    Usuario: admin@admin.com
    Senha: admin
