
# Scope
- Informa por quanto tempo os `bean CDI` deve existir
- Pacote: `javax.exterpise.context`

## @RequestScoped
- O estado do `bean CDI` só existe durante o scopo da requisição
- Após a requisição ser finalizada o `bean CDI` fica apto a ser coletado pelo GC
- Redirect Request & Foward Request

## @ViewScoped
## @SessionScoped
## @ApplicationScoped
