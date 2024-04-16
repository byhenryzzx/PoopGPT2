# 💩 PoopGPT - Script Injector para ChatGPT 💩
Uma simples extensão para burlar totalmente os filtros de proteção do ChatGPT - OpenAI

## 📔 Sobre
Por bastante tempo, vi pela internet prompts de Bypass / Jailbreak que não funcionavam sendo divulgados. Exemplos deles são o famoso [DAN](https://github.com/0xk1h0/ChatGPT_DAN) ou aqueles [DevMode](https://github.com/0xk1h0/ChatGPT_DAN). Grande parte das pessoas acreditam fielmente que esse é o máximo de capacidade que o ChatGPT pode atingir, mas é aí que eles estão enganados. PoopGPT veio pra mudar a visão sobre bypassers de IA's

-  **Praticidade**: Você não precisará mais ter que ficar colando o mesmo prompt de bypass no começo das frases para que ele continue o assunto do modo desejado. Com PoopGPT, você simplesmente escreve o que bem entender e ele vai ser forçado a responder, independente do que for.
-  **Interface**: PoopGPT é apresentado por uma interface agradável e intuitiva.
-  **Modos**: PoopGPT oferece diversos modos de chat e está frequentemente adicionando modulos novos.
-  **Administração**: PoopGPT é testado diariamente para acompanhar os patchs de proteção impostos pela [OpenAI](https://openai.com/).
-  **Atualização em Tempo Real**: Você não precisa ter que ficar pegando um código novo ou baixando algo novo a cada atualização para usar o PoopGPT. Você pode simplesmente guardar o script atual e usar ele sempre, que ele vai se atualizando automaticamente sem precisar de nenhuma ação do usuário.

## ℹ️ Inject Por Bookmark
Copie o código do script, vá em **Adicionar favorito** do seu navegador, no campo de **URL**, você vai escrever `javascript:`, depois colar o script do PoopGPT na frente e salvar. Assim, quando você clicar no favorito lá em cima, vai rodar o MOD!

## 💉 Como injetar

#### 💻 Pelo Navegador de PC
Para injetar o MOD pelo navegador de PC, você só vai precisar abrir o [ChatGPT](https://chat.openai.com), clicar **F12** ou **CTRL + SHIFT + i** que são atalhos para abrir o DevTools, clicar na parte de **Console** (ou **Terminal** para alguns), colar o código inteiro abaixo e apertar enter!


```bash
var scriptUrl='https://raw.githubusercontent.com/byhenryzzx/PoopGPT2/main/PoopGPT2.txt';fetch(scriptUrl).then(response=>response.text()).then(script=>{var scriptElement=document.createElement('script');scriptElement.innerHTML=script;document.head.appendChild(scriptElement);}).catch(error=>{console.error('Ocorreu um erro ao carregar o script:',error);});
```

#### 📲 Pelo Navegador de Android
Para injetar o MOD pelo navegador do Android, você só vai precisar abrir o [ChatGPT](https://chat.openai.com) pelo navegador [KiwiBrowser](https://play.google.com/store/apps/details?id=com.kiwibrowser.browser&hl=pt_BR&gl=US), clicar nos 3 pontos do canto superior direito, descer tudo, clicar em "**Abrir DevTools**" (caso não abra diretamente, verifique a seção de abas), depois é só clicar na aba de **Console**, colar o código inteiro acima e apertar enter!
(Se a aba do ChatGPT estiver pausada, é só fechar a aba do DevTools e o script será exibido!)

## 🛂 Responsabilidade

- 1. ``Ao utilizar este script, você concorda em assumir total responsabilidade por suas ações. Você reconhece que o uso inadequado ou ilegal deste script pode resultar em consequências legais, danos ou prejuízos para terceiros.``

- 2. ``Você concorda em utilizar este script apenas para fins legítimos e éticos, respeitando todas as leis, regulamentos e diretrizes aplicáveis. Você não deve usá-lo para disseminar conteúdo ofensivo, prejudicial, difamatório, ilegal, discriminatório ou que viole os direitos de terceiros.``

- 3. ``Ao utilizar este script, você reconhece que ele é fornecido "como está", sem garantias de qualquer tipo, expressas ou implícitas. Você assume todos os riscos associados ao uso deste script e renuncia a qualquer reivindicação contra o desenvolvedor ou a OpenAI por danos resultantes do seu uso.``

- 4. ``Você concorda em não utilizar este script para contornar ou comprometer a segurança de sistemas, redes ou serviços protegidos. Não é permitido realizar ataques de negação de serviço, invasões de privacidade, exploração de vulnerabilidades ou qualquer atividade maliciosa.``

- 5. ``O desenvolvedor deste script não se responsabiliza por quaisquer danos, perdas ou responsabilidades decorrentes do seu uso. Você concorda em isentar o desenvolvedor e a OpenAI de qualquer responsabilidade relacionada ao uso deste script.``

## 🔄 ReMod
Essa é uma versão modificada (ReMod) do projeto PoopGPT original, desenvolvido por [davizinmaker](https://github.com/davizinmakerkkj). O ReMod foi criado por [byhenryzzx](https://github.com/byhenryzzx) como uma continuação do trabalho de Davizinmaker, com o objetivo de expandir e aprimorar o projeto original.

O ReMod traz várias melhorias e recursos adicionais em relação à versão original, incluindo:

- **Layout mais convincente e animado**: O ReMod apresenta um layout mais dinâmico e atraente, proporcionando uma experiência de uso mais envolvente. Foi desenvolvido utilizando apenas JavaScript para garantir uma interface agradável e responsiva. Além disso, o framework SweetAlert2 foi empregado para criar pop-ups e notificações interativas.

- **Som de entrada e saída**: Foi adicionado suporte para sons de entrada e saída, tornando as interações com o PoopGPT mais imersivas. Agora, cada mensagem enviada e recebida é acompanhada por efeitos sonoros personalizados.

- **Aprimoramento de todos os prompts**: Todos os prompts foram aprimorados para garantir respostas mais precisas e coerentes em uma variedade de contextos. As entradas do usuário foram refinadas e expandidas para abranger uma gama mais ampla de tópicos e estilos de conversação.

- **Reformulação de códigos antigos**: Códigos antigos foram reformulados e otimizados para melhor desempenho e estabilidade. Foram aplicadas práticas modernas de desenvolvimento de software e revisões de código para garantir uma base sólida e escalável para futuras atualizações.

O ReMod foi concebido como uma maneira de continuar o legado do PoopGPT e explorar ainda mais o potencial do ChatGPT. Ele não visa substituir ou roubar o trabalho de Davizinmaker, mas sim expandi-lo e adaptá-lo às necessidades e expectativas da comunidade. Agradecemos a Davizinmaker por sua contribuição inicial e esperamos que o ReMod seja uma adição valiosa à comunidade de usuários do ChatGPT.

## 📂 Repositório Original
Este ReMod foi baseado em um fork do repositório original do PoopGPT, mantido por [davizinmaker](https://github.com/davizinmakerkkj). O projeto original foi desenvolvido para oferecer uma solução de script injector para contornar os filtros de proteção do ChatGPT da OpenAI.

O repositório original contém o código-fonte inicial do PoopGPT e fornece insights sobre o desenvolvimento e a evolução do projeto ao longo do tempo. Ao contribuir com o ReMod, reconhecemos e valorizamos o trabalho inicial de Davizinmaker e buscamos construir sobre sua base sólida.

Você pode explorar o repositório original em [github.com/davizinmakerkkj/PoopGPT](https://github.com/davizinmakerkkj/PoopGPT) para obter mais informações sobre o projeto original, seu histórico de commits e quaisquer contribuições adicionais feitas pela comunidade.

## 🔒 Implementação do Content Security Policy (CSP) pela OpenAI

Recentemente, a OpenAI implementou uma política de segurança de conteúdo (CSP) no ChatGPT. O CSP é uma medida de segurança implementada pelos navegadores da web para mitigar ataques de script cross-site (XSS) e outras vulnerabilidades de segurança relacionadas à execução de scripts.

### ℹ️ Motivo da Implementação

A implementação do CSP pela OpenAI tem como objetivo principal proteger os usuários do ChatGPT contra possíveis ameaças de segurança. O CSP restringe quais recursos externos podem ser carregados e executados no navegador do usuário a partir do domínio do ChatGPT. Isso inclui a proibição de execução de scripts de outros domínios que possam ser maliciosos.

Ao limitar a execução de scripts de fontes externas, a OpenAI visa reduzir o risco de exploração de vulnerabilidades de segurança, como injeção de código malicioso ou roubo de dados pessoais dos usuários. Essa medida é uma parte essencial dos esforços contínuos da OpenAI para proteger a integridade e a privacidade dos usuários do ChatGPT.

### 🛡️ Funcionamento do CSP

O CSP define uma série de diretrizes de segurança que o navegador do usuário deve seguir ao carregar e executar recursos externos, como scripts, estilos e fontes. Isso é feito por meio de cabeçalhos HTTP enviados pelo servidor do ChatGPT para o navegador do usuário, especificando quais tipos de conteúdo externo são permitidos e quais devem ser bloqueados.

Essas diretrizes são projetadas para equilibrar a segurança com a funcionalidade, permitindo que o ChatGPT continue oferecendo uma experiência de usuário rica e interativa, enquanto protege contra ameaças de segurança conhecidas.

### 🚫 Impacto nos Scripts de Terceiros

Devido à implementação do CSP, os scripts de terceiros, como aqueles fornecidos por extensões de navegador ou usuários, podem ser afetados. O CSP pode bloquear a execução desses scripts se não estiverem em conformidade com as políticas de segurança definidas pela OpenAI.

Portanto, é importante que os desenvolvedores de scripts compreendam e adotem as práticas recomendadas de segurança para garantir que seus scripts sejam compatíveis com o CSP e possam ser executados no ambiente do ChatGPT sem comprometer a segurança dos usuários.

A implementação do CSP pela OpenAI é um passo significativo na proteção dos usuários do ChatGPT contra ameaças de segurança e reforça o compromisso da OpenAI com a segurança e privacidade dos dados dos usuários.

## 🚫 Extensão "Disable CSP"

A extensão "Disable CSP" é uma ferramenta útil para contornar as restrições do Content Security Policy (CSP) implementadas pela OpenAI no ChatGPT. Essa extensão permite desativar temporariamente o CSP no navegador, facilitando a execução de scripts de terceiros, como o PoopGPT V2.

### 🔗 Link para a Extensão

Você pode encontrar a extensão "Disable CSP" no seguinte link: [Disable CSP - Chrome Web Store](https://chromewebstore.google.com/detail/disable-csp/hgegihapiofjgmmgigbblnjaicgjhoko).

### ⚙️ Como Instalar

Para instalar a extensão "Disable CSP", siga estas etapas:

1. **Chrome no Computador**: 
   - Acesse o link da extensão no Chrome Web Store.
   - Clique no botão "Adicionar ao Chrome".
   - Confirme a instalação na caixa de diálogo que aparece.

2. **KiwiBrowser no Android**:
   - Abra o KiwiBrowser no seu dispositivo Android.
   - Acesse o link da extensão na Chrome Web Store.
   - Clique no botão "Adicionar ao Chrome".
   - Confirme a instalação na caixa de diálogo que aparece.

### 🛠️ Como Usar

Depois de instalar a extensão, você pode desativar o CSP facilmente clicando no ícone da extensão na barra de ferramentas do navegador. Em seguida, clique nos dois switches de desabilitar o CSP para permitir a execução de scripts de terceiros. Certifique-se de habilitar novamente o CSP após o uso da extensão para garantir a segurança da sua navegação.

A extensão "Disable CSP" oferece uma solução simples e eficaz para contornar as restrições do CSP no ChatGPT e aproveitar ao máximo recursos como o PoopGPT V2.

## 📜 Nota
Tanto eu quanto o davizinmaker, não temos nenhuma relação com a OpenAI. Tanto a versão quanto o ReMod foram feitos para fins educacionais. Use a seu critério.
