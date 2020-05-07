[Ir para .NET Core](../dotnet.md)

# Entity Framework - Migrations

## Configurar Code-First

Considerando que as classes já estejam criadas usando DDD

### Instalar os pacotes

- Microsoft.EntityFrameworkCore.Tools
- Microsoft.EntityFrameworkCore.Design
- Pomelo.EntityFrameworkCore.MySql

### Ativando Migration

`Add-Migration [nome da versão]`

### Persistir no Banco de Dados

`Update-Database`

### Reverter versão

`Remove-Migration`

