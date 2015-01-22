# MongoDB Shell Enhancements

## Atenção
Essas heranças são bastante uteis para mim, mas podem não fazer sentido
para alguém. Tenha a liberdade dizer o que quiser e por favor envie 'pull requests';
- Não funciona no 'ruindowns'
- Não roda com shells or db servers < 2.2 (atual)
- Atualizações estão sendo experimentadas (veja as notas na seção de API)  
## Instalação


Clone o repositório e rode `make`. Isso vai 'linkar' `mongo_hacker.js` para `.mongorc.js` seu diretório home:

```sh
git clone https://github.com/TylerBrock/mongo-hacker.git
rm -rf ~/.mongorc.js # may be needed as we don't force the link anymore
cd mongo-hacker
make
```

