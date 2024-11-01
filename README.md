# M10semana2

Passo a passo

# Instalar o Yarn
Antes de baixar os arquivos é importante baixar o Yarn para nao dar erros, isso é feito usando : `npm install -g yarn`

# Instalar os arquivos
Usei o comando `npx @backstage/create-app@latest` para baixar os arquivos.

Porem,de cara ja tive um erro de cara que não consegui progredir:

```
executing yarn install ✖
...
Error: Could not execute command yarn install
```


### Detalhes específicos dos pacotes que falharam ao serem compilados:
- `better-sqlite3`
- `tree-sitter-json`
- `tree-sitter-yaml`
- `isolated-vm`
- `cpu-features`

### Com isso tentei baixar as ferramentas usando `npm install --global windows-build-tools` mas obtive um erro relacionado a descontinuação do pacote e ao uso de uma implementação desatualizada.

  ![image](https://github.com/user-attachments/assets/21fb408e-760e-4d76-8832-765fdd304915)


### Conclusão :
Não consegui nem passar do passo 1 ,  se possivel, gostaria de tentar com você uma outra hora.
