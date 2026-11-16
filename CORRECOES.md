# Correções

O texto parte de uma digitalização da Bíblia do Padre Manuel de Matos Soares (1956), disponível publicamente em [Dancrf/biblia-db](https://github.com/Dancrf/biblia-db). O texto foi revisto, corrigido e atualizado.

## O que foi feito

- **Acordo Ortográfico de 1990**, como se aplica em Portugal: `Egipto → Egito`, `acção → ação`, `baptismo → batismo`, `óptimo → ótimo`, `recto → reto`. Mantêm-se `facto`, `pacto` e `tacto`, onde a consoante se lê.
- **Formas de Portugal** em vez das brasileiras: `demônio → demónio`, `Gênesis → Génesis`, `Crônicas → Crónicas`, `conosco → connosco`.
- **Erros da digitalização**: acentos antigos (`sòmente → somente`, `vêem → veem`), trema (`cinqüenta → cinquenta`), acentos em falta (`discipulos → discípulos`), gralhas (`fllho → filho`, `die Israel → de Israel`) e hífenes soltos.
- **Remissões para notas** (`(ver nota)`): 1722 foram retiradas, porque as notas não fazem parte do texto digitalizado.
- **Versículos repetidos**: a fonte repete alguns (por exemplo Js 8,9); fica a cópia corrigida.

No total: **477 formas diferentes alteradas, em 2 713 ocorrências**. A lista completa, com contagens, está em [docs/ortografia.md](docs/ortografia.md).

## O que ainda está em revisão

- Há **570 palavras** que o corretor ortográfico não reconhece (a maioria são termos bíblicos legítimos, como *siclo*, *éfode* ou *hissopo*; algumas podem ser erros por apanhar). A lista está em [docs/por-rever.md](docs/por-rever.md). Se encontrares um erro, abre uma *issue*.
- **Sem notas de rodapé**: a digitalização não as inclui.
- **Numeração**: a da edição tem saltos (por exemplo em Provérbios).
