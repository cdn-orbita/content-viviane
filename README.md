# Descrição
Content Delivery Network (cdn) para Órbita Marketing Digital Ltda. servindo a Estética Viviane Magalhães.

Para acessar as imagens, utilizamos jsDelivr (OpenSource) (https://www.jsdelivr.com/)

Documentação: https://www.jsdelivr.com/documentation

# Requisitos
Conta autorizada para modificar o repositório local (content-viviane). Contate um programador para lhe dar permissões.

O repositório precisa ser público para que isto funcione.

# Acessar imagens do repositório
## Modelo do link para acessar a imagem do repositório:

cdn.jsdelivr.net/gh/username/repositorio/nome-da-imagem.ext

## Link rápido:

cdn.jsdelivr.net/gh/cdn-orbita/content-viviane/nome-da-imagem.ext

# Inserindo imagens
Vincule uma pasta dedicada para conter um acesso ao repositório. Ex:

F:/Desktop/git/repositorio

## Vincule pelo console cmd usando:
```
git init
git remote add origin https://github.com/cdn-orbita/content-viviane.git
```

Faça login no github para confirmar permissões e poder começar a enviar imagens.

Insira a imagem a ser enviada na pasta dedicada mencionada anteriormente.

## Agora dê upload utilizando:
```
git add nome-da-imagem.ext
git commit -m "mensagem teste de commit"
git push
```
