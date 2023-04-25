# CONCEITO BÁSICOS 

### SERÁ ABORDADO:

1. TIPOS DE DADOS
2. OPERADORES MATEMÁTICOS
3. ENTRADA|SAÍDA

#### OS PRINCIPAIS TIPOS DE DADOS

1. INTEGER
    REPRESENTA COMO NA MATEMÁTICA NUMEROS INTEIROS, CONJUNTO DE NUMEROS POSITIVOS, NEGATIVO E 0.

        integerNumber = 20

    .class mostra o real tipo que foi atribuido a variavel

        integerNumber.class

2. FLOAT
    REPRESENTA OS NUMEROS FLUTUANTES EX. 10.02

        floatNumber = 20.05
3. BOOLEAN
    REPRESENTA O VALOR VERDADEIRO OU FALSO.

        rubyFreeCourse = true

4. STRING
    REPRESENTA UM CONJUNTO DE LETRAS, TEXTO.

        happiness = 'programing with ruby'

5. ARRAY 
    PERMITE ARMAZENAR UMA LISTA ORDENADA DE DADOS EM UM UNICO OBJETO, PARA DEFINIR SE UTILIZA COLCHETES.

        bitcodeArray =[0, 1, 3, 'dois']

    para acessa uma posição no array.

        bitcodeArray[2] 
    
    acessa a terceira posição no array  
    
6. SYMBOL
    E UM TIPO DE DADO SEMELHANTE A STRING A DIFERENÇA QUE O OBJETO DECLARADO E IMUTAVEL.

        oneBitSymbol = :ruby_symbol

   OBJECT_ID
    MOSTRA QUAL A POSIÇÃO DA MEMORIA O MESMO FOI SALVO.

        oneBitSymbol.object_id


7. HASH
    REPRESENTA UMA COLEÇÃO DE DADOS ORGANIZADOS POR CHAVES UNICAS E SEUS VALORES.

        oneBitHash = {course: 'ruby', language: 'pt-br'}

#### OPERADORES MATEMÁTICOS
    PARA RESOLVER OPERAÇÕES MATEMATICAS

    1. + ADIÇÃO
    2. - SUBTRAÇÃO
    3. * MULTIPLICAÇÃO
    4. / DIVISAÇÃO
    5. % MODULO
    6. ** EXPOENTE

#### ENTRADA | SAÍDA

EX:

    saída de dado

        print 'Digite seu nome: '



     Recebendo uma entrada do teclado

        name = gets.chomp

    saída utilizando puts
    use códigos ruby dentro de uma string com #{code}

        puts "Hello #{name}!

        
    


