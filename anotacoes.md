# Anotações da Documentação .NET 🟣

# Método Main():

Quando um aplicativo C# é iniciado, o método **Main**(), é o primeiro a ser invocado, ou seja, executado. Se caso houver mais de um **Main**() na aplicação, será necessário compilar o programa com a opção do compilador **StartupObject** para especificar qual método Main() será invocado primeiro.
A partir do C# 9 é possível omitir o método Main() e escrever o programa como se já tivesse um método main ali.

# Modificadores de Acesso:

Todos os membros e tipos possuem um nível de acessibilidade, esse nível controla se eles podem ser usados em outro código no assembly. Um assembly é um .dll ou .exe criado ao selecionar um ou mais arquivos .cs em uma única compilação. Abaixo vou por o que eu tenho menos familiaridade:

**Private**: O tipo ou membro só pode ser acessado pelo código na mesma classe ou struct.

**Protected**: O tipo ou membro só pode ser acessado pelo código na mesma classe ou em uma classe que é derivada dessa classe.

**Internal**: O tipo ou membro só pode ser acessado pelo código que faz parte da mesma compilação.