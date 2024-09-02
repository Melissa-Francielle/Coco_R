# Trabalho de Compiladores - Apresentando um Analisador Sintático

**Universidade Estadual do Norte do Paraná - UENP**  
**Disciplina:** Compiladores  
**Profº:** Wellington Della Mura  
**Discentes:** Joana Shizu Ono De Camargo e Melissa Francielle dos Santos

---

O analisador sintático usado nesse trabalho é o **Coco/R**. O Coco/R é um gerador de compilador desenvolvido pela ETHZ e passou a ser desenvolvido logo após pela Universidade de Linz. Esse gerador utiliza uma gramática atribuída de uma linguagem de origem e gera um scanner e um analisador para essa linguagem. Seu criador, o cientista austríaco **Hanspeter Mössenböck**.

## Instalação

1. Pelo prompt:
    ```bash
    dotnet tool install --global CocoR --version 2014.12.25
    ```
2. Baixando o executável pelo site:
    [https://ssw.jku.at/Research/Projects/Coco/](https://ssw.jku.at/Research/Projects/Coco/)

## Dicas

- No prompt, utilize o comando `coco` para verificar as opções de configurações do programa e para fazer quaisquer chamadas de uso.
- Os arquivos de gramáticas devem estar na extensão `.ATG` para garantir o funcionamento.
- No site do Coco/R, eles apresentam tutoriais e manuais para o usuário, além de fornecer exemplos de gramáticas e uso.

## Principais componentes para o funcionamento da conversão

- `Coco.exe` ou instalado pelo prompt
- `Parser.frame`
- `Scanner.frame`

**Nota:** Tanto o `Parser.frame` quanto o `Scanner.frame` são adquiridos no site oficial do Coco/R, mas também podem ser criados pelo usuário.

## Para o mínimo funcionamento correto do código

- `Main.cs`
- `Parser.cs`
- `Scanner.cs`
- `input.txt`
