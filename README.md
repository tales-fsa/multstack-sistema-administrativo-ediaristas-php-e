## Projeto sistema administrativo da plataforma E-Diaristas

Desenvolvido no curso Multi-Stack da TreinaWeb

### Instalando o projeto

#### Clonar o repositório

```
git clone https://github.com/tales-fsa/multstack-sistema-administrativo-ediaristas-php-e.git
```

#### Instalar as dependências

```
composer install
```
Ou em ambiente de desenvolvimento

```
composer update
```

#### Criar arquivo de configurações de ambiemte

Copiar o arquivo de exemplo `.env.example` para `.env` na raiz do projeto
configurar os detalhes da aplicação e conexão com o banco de dados.

#### Criar a estrutra no banco de dados

```
php artisan migrate
```

#### Iniciar o servidor de desenvolvimento

```
php artisan serve
```


