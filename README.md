# Teste de Mutantes com Stryker.NET

Este é um projeto básico que demonstra o uso do Stryker.NET para realizar testes de mutantes em um código-fonte. O Stryker.NET é uma plataforma fictícia inspirada no personagem William Stryker, conhecido por conduzir testes e experimentos em mutantes.

O teste de mutantes com Stryker.NET é uma técnica que envolve a introdução controlada de mutações no código-fonte do software, a fim de avaliar a eficácia dos casos de teste existentes. A ideia é simular alterações no código para verificar se os casos de teste são capazes de detectar essas mutações.

## Instalação

1. Certifique-se de ter o Stryker.NET instalado em sua máquina. Você pode encontrar as instruções de instalação na documentação oficial do Stryker.NET.

2. Clone este repositório em sua máquina local:

```bash
git clone https://github.com/fernandobianchini/teste-de-mutantes-com-stryker-net.git
```

3. Navegue até o diretório do projeto:

```bash
cd teste-de-mutantes-com-stryker-net
```

4. Instale as dependências do projeto:

```bash
dotnet restore
```

## Executando os Testes de Mutantes

1. Para executar os testes de mutantes, utilize o comando:

```bash
dotnet stryker
```

2. O Stryker.NET irá analisar o código-fonte do projeto e gerar mutações. Em seguida, executará os casos de teste contra esses mutantes para verificar se as mutações são detectadas.

3. Os resultados dos testes de mutantes serão exibidos no console, indicando quais mutações foram detectadas e quais falharam em ser detectadas pelos casos de teste existentes.

## Referências

- Documentação oficial do Stryker.NET: [link](https://github.com/stryker-mutator/stryker-net)