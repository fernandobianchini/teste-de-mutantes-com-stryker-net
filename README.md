# Teste de Mutantes com Stryker.NET

Este � um projeto b�sico que demonstra o uso do Stryker.NET para realizar testes de mutantes em um c�digo-fonte. O Stryker.NET � uma plataforma fict�cia inspirada no personagem William Stryker, conhecido por conduzir testes e experimentos em mutantes.

O teste de mutantes com Stryker.NET � uma t�cnica que envolve a introdu��o controlada de muta��es no c�digo-fonte do software, a fim de avaliar a efic�cia dos casos de teste existentes. A ideia � simular altera��es no c�digo para verificar se os casos de teste s�o capazes de detectar essas muta��es.

## Instala��o

1. Certifique-se de ter o Stryker.NET instalado em sua m�quina. Voc� pode encontrar as instru��es de instala��o na documenta��o oficial do Stryker.NET.

2. Clone este reposit�rio em sua m�quina local:

```bash
git clone https://github.com/fernandobianchini/teste-de-mutantes-com-stryker-net.git
```

3. Navegue at� o diret�rio do projeto:

```bash
cd teste-de-mutantes-com-stryker-net
```

4. Instale as depend�ncias do projeto:

```bash
dotnet restore
```

## Executando os Testes de Mutantes

1. Para executar os testes de mutantes, utilize o comando:

```bash
dotnet stryker
```

2. O Stryker.NET ir� analisar o c�digo-fonte do projeto e gerar muta��es. Em seguida, executar� os casos de teste contra esses mutantes para verificar se as muta��es s�o detectadas.

3. Os resultados dos testes de mutantes ser�o exibidos no console, indicando quais muta��es foram detectadas e quais falharam em ser detectadas pelos casos de teste existentes.

## Refer�ncias

- Documenta��o oficial do Stryker.NET: [link](https://github.com/stryker-mutator/stryker-net)