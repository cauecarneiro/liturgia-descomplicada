# Liturgia Descomplicada

O folheto completo da missa do dia no iPhone e no iPad, para quem acompanha a liturgia pelo celular.

App na App Store · iPhone e iPad · 2026

[Liturgia Descomplicada na App Store](https://apps.apple.com/br/app/liturgia-descomplicada/id6761694378)

O código-fonte do app não está neste repositório, que guarda só a licença MIT.

## O que faz
- Mostra as leituras, o salmo e o evangelho do dia, conforme o calendário litúrgico.
- Traz um devocionário com busca e favoritos.
- Funciona dentro da igreja, sem sinal: o app busca o conteúdo pela rede, guarda no aparelho e já deixa os próximos dias carregados.

## Meu papel
Projeto solo, da arquitetura à publicação na App Store (no ar desde 09/04/2026).

## Como foi feito
- Offline primeiro: tenta a rede, guarda o conteúdo no aparelho e carrega os próximos dias com antecedência.
- Camadas separadas: domínio, dados e apresentação, com injeção de dependência (Clean Architecture com MVVM).
- Conteúdo vindo de uma API, lido com URLSession e Codable.
- Projeto gerado com XcodeGen.
- Interface pensada a partir das Human Interface Guidelines da Apple.

## Tecnologias
Swift, SwiftUI, SwiftData, URLSession, Codable e XcodeGen.

## Como rodar
Baixe o app na App Store pelo link acima. Como o código não está publicado aqui, não há passos de compilação.

---
Feito por Cauê Crillanovick · [portfólio](https://cauecarneiro.github.io/portfolio/) · [LinkedIn](https://www.linkedin.com/in/cau%C3%AA-carneiro)
