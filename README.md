Sistema Expert - Deep Scan
Sobre o projeto

Esse projeto é um programa em C# que simula uma análise de sistema (tipo um “scan” de hardware).
Ele mostra na tela o que está acontecendo enquanto executa, como se fosse um sistema real processando dados.

A ideia principal não é só rodar, mas mostrar um conceito de IHC na prática.

Objetivo

Aplicar a 1ª heurística de Nielsen:

Visibilidade do status do sistema

Ou seja, o sistema sempre mostra pro usuário o que ele está fazendo.

Como funciona

O programa:

Limpa a tela
Mostra um título
Vai exibindo etapas do processo (CPU, memória, etc.)
Simula um tempo de processamento com Thread.Sleep
Atualiza a mesma linha com \r
Mostra uma mensagem final quando termina
Onde entra a heurística

Durante a execução, o sistema mostra coisas como:

Verificando CPU...
Lendo Memória RAM...
Sincronizando SDK...
Validando Permissões...
Finalizando...

Isso evita que o usuário ache que travou ou que não está acontecendo nada.

Por que isso é importante?

Sem esse tipo de feedback:

O usuário pode ficar perdido
Pode achar que deu erro
Pode até fechar o programa sem precisar

Com isso:

Fica claro que o sistema está rodando
Passa mais confiança
Melhora a experiência
Como rodar

Só precisa ter o .NET instalado e rodar:

dotnet run
Conclusão

Mesmo sendo um programa simples, dá pra ver como mostrar o que está acontecendo faz diferença.

Pequenos detalhes na interface já melhoram bastante a interação com o usuário.
