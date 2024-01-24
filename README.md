# Projeto 7 - README

## Descrição
O Projeto 7 é um aplicativo simples desenvolvido com o objetivo de aprender e colocar em prática desenvolvendo a teoria.

## Instalação
Siga as instruções abaixo para configurar o ambiente de desenvolvimento e instalar as dependências necessárias para rodar o projeto:

1. O código foi escrito em Python 3.9, portanto, você poderá utilizar outra IDE que tenha as especificações similares da versão (exemplo: VisualCode, PyCharm, no Android Pydroid3, etc.)
2. Utilizei métodos simples para que qualquer um consiga trabalhar com o código.
3. Escolha o projeto 7 e o número da versão para começar à compilar em sua máquina.
4. Caso não saiba ou tenha dificuldades em rodar o projeto 7 da versão 1.1.0 em diante, siga estes passos:
   - Se estiver com o terminal aberto no computador, digite pip install tkinter.
   - Aguarde terminar a instalação e então rode o aplicativo py.

## Utilização
Para utilizar o Projeto 7, siga as etapas abaixo:

1. Utilize da forma como você quiser os códigos expostos de forma responsável e segura.
2. Caso não consiga compilar o arquivo, reveja estas instruções fornecidas.
3. Lembre-se que este código disposto é para fins didáticos, mas nada impede que possa usá-lo como um outro produto que esteja desenvolvendo ou em outro projeto qualquer, fique à vontade de usá-lo
4. Preste atenção aos blocos que foram implementados e testados antes da divulgação do mesmo.

Veja como utilizar (iniciantes) Exemplo de código:

código do python (baseado no projeto final, do Módulo 2, do desafio IBM SkillsBuild do Match! turma SETEMBRO/2023):
# Cadastro de Participantes
nome = input("Digite seu nome: ")
idade = int(input("Digite sua idade: "))
endereco = input("Digite seu endereço: ")
residencia_sp = input("Você reside em São Paulo? (S/N): ")

# Verificação de Condições
if idade >= 18 and residencia_sp.upper() == "S":
    # Verificação de Vagas Disponíveis
    vagas_disponiveis = 50
    if vagas_disponiveis > 0:
        # Feedback aos Participantes
        print("Inscrição validada! Você está inscrito no evento.")
        vagas_disponiveis -= 1
    else:
        print("As inscrições estão encerradas.")
else:
    # Feedback aos Participantes
    if idade < 18:
        print("Desculpe, apenas maiores de idade podem se inscrever.")
    if residencia_sp.upper() != "S":
        print("Desculpe, a participação é restrita a moradores de São Paulo.")

## Estrutura de Arquivos
A estrutura de arquivos do Projeto 7 está organizada da seguinte forma:

- Projeto 7 v.1.0: base comum (terminal/ambiente).
- Projeto 7 v.1.1.0: criado com a biblioteca Tkinter para saída gráfica.
- Projeto 7 v.1.1.1: adicionado e complementado atributos e comentários específicos de cada instrução do bloco programável.
- Projeto 7 v.2.0: criado para desenvolvimento web com a biblioteca Flask.

## Versionamento
O Projeto 7 utiliza um sistema de versionamento baseado em Python 3.x. As versões são numeradas da seguinte forma:

- [Projeto 7 v.1.0]: Primeiro aplicativo simples, compilado diretamente no Terminal (sem instruções nos blocos). [Data: dez/2024]
- [Projeto 7 v.1.1.0]: Segundo aplicativo simples melhorado. [Data: dez/2023]
- [Projeto 7 v.1.1.1]: Terceiro aplicativo simples atualizado com novas regras PEP para outros desenvolvedores ou entusiastas/estudantes. [Data: jan/2024]
- [Projeto 7 v.2.0]: Quarto aplicativo simples aprimorado para a versão web com a biblioteca Flask. [Data: jan/2024]

## Histórico de Versões
A seguir estão as principais alterações e melhorias em cada versão do projeto:

| Versão | Descrição |
|--------|-----------|
| v.1.0  | Primeira versão do projeto |
| v.1.1.0 | Segunda versão com melhorias e biblioteca tkinter |
| v.1.1.1 | Terceira versão com regras PEP atualizadas |
| v.2.0 | Quarta versão com implementação web usando Flask |

## Contribuição
Você pode contribuir para o projeto de várias maneiras, incluindo:

- Abrir problemas (issues) relatando bugs ou sugerindo melhorias
- Fazer um fork do repositório e enviar solicitações de pull request com suas alterações

Consulte o arquivo CONTRIBUTING.md para obter mais informações sobre como contribuir.

## Licença
O Projeto 7 está disponível sob a MIT. Consulte o arquivo LICENSE.md para obter mais informações.

## Agradecimentos
Gostaríamos de agradecer à todos os participantes envolvidos no curso livre Programa Deu Match! IBM SkillsBuild da turma de Setembro/2023 e a oportunidade deste aprendizado inicial de Python.
