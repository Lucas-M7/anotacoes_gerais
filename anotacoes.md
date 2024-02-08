# Anotações da Documentação .NET 🟣

# Método Main():

Quando um aplicativo C# é iniciado, o método **Main**(), é o primeiro a ser invocado, ou seja, executado. Se caso houver mais de um **Main**() na aplicação, será necessário compilar o programa com a opção do compilador **StartupObject** para especificar qual método Main() será invocado primeiro.
A partir do C# 9 é possível omitir o método Main() e escrever o programa como se já tivesse um método main ali.

# Modificadores de Acesso:

Todos os membros e tipos possuem um nível de acessibilidade, esse nível controla se eles podem ser usados em outro código no assembly. Um assembly é um .dll ou .exe criado ao selecionar um ou mais arquivos .cs em uma única compilação. Abaixo vou por o que eu tenho menos familiaridade:

**Private**: O tipo ou membro só pode ser acessado pelo código na mesma classe ou struct.

**Protected**: O tipo ou membro só pode ser acessado pelo código na mesma classe ou em uma classe que é derivada dessa classe.

**Internal**: O tipo ou membro só pode ser acessado pelo código que faz parte da mesma compilação.

# Programação Assíncrona em C#

É uma abordagem de programação que permite que um programa seja executado em operações não sequenciais. Essa abordagem permite que outras tarefas sejam executadas enquanto aguarda a conclusão de operações demoradas.

# Async / Await

A palavra async é usada para marcar métodos assíncron.
A palavra await é usada para indicar pontos de espera para operações assíncronas.


Protocolos HTTP (Hypertext Transfer Protocol) são a base da comunicação na web, permitindo que os clientes (como navegadores da web) se comuniquem com servidores para solicitar e receber recursos, como páginas da web, imagens e arquivos. Embora seja uma tecnologia fundamental e amplamente adotada, ainda há uma série de erros comuns que podem surgir durante a interação com o protocolo HTTP. Aqui estão alguns dos principais erros e suas causas:

1. **Erro 404 - Página não encontrada**: Este é um dos erros mais comuns que os usuários encontram ao navegar na web. Ele ocorre quando o servidor não pode encontrar o recurso solicitado. Isso pode acontecer devido a uma URL mal formada, alteração no nome do recurso ou o recurso não está mais disponível no servidor.

2. **Erro 500 - Erro interno do servidor**: Este erro indica que algo deu errado no servidor, mas não especifica o problema exato. Pode ser causado por falhas no código do servidor, problemas de configuração ou sobrecarga do servidor.

3. **Erro 403 - Acesso proibido**: Este erro ocorre quando o servidor se recusa a atender a uma solicitação, geralmente devido a permissões insuficientes do usuário. Isso pode acontecer se o recurso estiver protegido por autenticação ou se o servidor estiver configurado para negar o acesso a determinados diretórios ou arquivos.

4. **Erro 301 e 302 - Redirecionamento permanente e temporário**: Esses erros ocorrem quando o servidor redireciona o cliente para outra URL. O erro 301 indica um redirecionamento permanente, enquanto o erro 302 indica um redirecionamento temporário. Os redirecionamentos são comuns quando um recurso foi movido para uma nova localização.

5. **Erro 400 - Solicitação inválida**: Este erro ocorre quando o servidor não consegue entender ou processar a solicitação do cliente devido a sintaxe inválida, parâmetros ausentes ou malformados, ou outros problemas relacionados à solicitação.

6. **Erro 504 - Gateway Timeout**: Esse erro ocorre quando um servidor intermediário (como um proxy) não recebe uma resposta oportuna do servidor de origem. Isso pode acontecer devido a problemas de conectividade, sobrecarga do servidor ou tempos de resposta muito longos.

7. **Erro 401 - Não autorizado**: Este erro é semelhante ao erro 403, mas especifica que a solicitação requer autenticação. Isso geralmente ocorre quando um usuário tenta acessar um recurso protegido sem fornecer credenciais válidas.

8. **Erro 503 - Serviço indisponível**: Este erro indica que o servidor está temporariamente indisponível devido a sobrecarga ou manutenção. Geralmente, o servidor especifica quando espera estar disponível novamente na resposta.

Esses são apenas alguns dos erros mais comuns que os usuários podem encontrar ao interagir com o protocolo HTTP. É importante que desenvolvedores e administradores de sistemas estejam cientes desses erros e saibam como diagnosticá-los e corrigi-los para garantir uma experiência de usuário suave e confiável na web.
