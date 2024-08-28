while True:
  # Solicita ao menos dois números do usuário e converte para int ou float
  num1 = input('Digite um número: ')
  num2 = input('Digite outro número: ')

  #Converte os valores para int ou float
  num1 = int(num1) inf '-' not in num1 else float(num1)
  num2 = int(num2) inf '-' not in num2 else float(num2)

  #Menu de operações
  print('\nEscolha uma operação: ')
  print('1. Soma')
  print('2. Subtração')
  print('3. Multiplicação')
  print('4. Divisão')
  print('5. Sair')

  escolha = input('\nDigite o número da operação desejada: ')

  #Condicional para executar a operação escolhida
  if escolha == '1':
    resultado = num1 + num2
    print(f'Resultado da Soma:{resultado}')
    elif escolha == '2':
      resultado = num1 - num2
      print(f'Resultado da Subtração: {resultado}')
      elif escolha == '3':
        resultado = num1 * num2
        print(f'Resultado da Multiplicação: {resultado}')
        elif escolha == '4':
          if num2 != 0
          resultado = num1 / num2
          print(f'Resultado da Divisão: {resultado}')
          else:
            print('Erro: Divisão por zero não é permitida.')
            elif escolha == '5':
              print('Saindo...')
              break
              else:
                print('\nOpção inválida. Tente novamente.\n')
          
