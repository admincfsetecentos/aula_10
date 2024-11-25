# Scripts Disponíveis
No diretório do projeto, posso rodar os seguintes comandos: "npm start". Esse comando executa o aplicativo no modo de desenvolvimento. Para visualizar no navegador, basta abrir http://localhost:3000. A página será recarregada automaticamente sempre que eu fizer alterações. Além disso, erros de lint (caso ocorram) serão exibidos no console. "npm test": Esse comando inicia o runner de testes em modo interativo, observando qualquer alteração no código. Se eu precisar de mais informações sobre como executar os testes, posso consultar a seção sobre execução de testes na documentação. "npm run build": Esse comando cria a versão otimizada do meu aplicativo para produção na pasta build. O React será empacotado corretamente em modo de produção e a construção será otimizada para garantir o melhor desempenho. Os arquivos serão minificados, e seus nomes incluirão hashes para controle de cache. Agora, meu aplicativo estará pronto para ser publicado! Se precisar de mais detalhes sobre como realizar a implantação, posso consultar a documentação específica. "npm run eject": Atenção: Essa é uma operação irreversível. Depois de usar o eject, não tem como voltar atrás! Se eu não estiver satisfeito com as opções de configuração ou ferramentas de construção, posso usar o comando eject a qualquer momento. Esse comando remove a dependência única de construção do meu projeto e copia todas as configurações e dependências (como webpack, Babel, ESLint, etc.) diretamente para o meu projeto. Com isso, terei controle total sobre elas. Todos os outros comandos continuarão funcionando normalmente, mas agora apontando para os scripts copiados, que poderei ajustar conforme necessário. A partir desse momento, o gerenciamento do projeto estará completamente sob minha responsabilidade. Não preciso usar o eject. As configurações padrão atendem bem a projetos pequenos e médios, então não há obrigatoriedade de usá-lo. No entanto, entendo que, quando estiver pronto para personalizar as configurações do projeto, o eject pode ser útil.

# React Components
Este código cria um componente Menu em "React" que exibe uma lista de pratos de um cardápio. Cada prato é representado por um objeto com informações como nome, imagem, descrição e preço. O componente utiliza a biblioteca "reactstrap" para estruturar e exibir o conteúdo de maneira responsiva e estilizada.

React é a biblioteca que estamos usando para criar a interface de usuário.
useState é um "hook" que permite criar variáveis de estado dentro de um componente funcional.
Media é um componente do reactstrap que facilita a organização do conteúdo, especialmente para layouts com imagens e textos.

O "useState" inicializa a variável dishes, que é um array de objetos representando os pratos do cardápio. Cada objeto contém detalhes como o nome, imagem, categoria, preço e descrição do prato.

Usou-se a função "map" para percorrer o array "dishes" e gerar uma lista de componentes "div" para cada prato.
Cada prato tem uma imagem, nome e descrição exibidos de forma organizada, usando o componente Media do "reactstrap".

O JSX dentro do "return" define a estrutura final do componente. Colocou-se todos os pratos dentro de um "Media list" (lista de itens de mídia), que será exibido em um layout responsivo, usando "classes" como container e "row" para alinhamento.
"{menu}" é a lista de pratos mapeada que é inserida dentro da estrutura HTML.

O Menu é exportado para ser usado em outros arquivos do projeto.