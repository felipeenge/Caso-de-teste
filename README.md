# Caso de teste, cenário de teste e bug report
 Descrição do que é um caso de teste, cenário de teste, e bug report.

# Caso de teste:

Um caso de teste consiste de certos conjuntos de condições que precisam ser verificados para testar uma aplicação ou software. Consiste de vários parâmetros, como título único, precondições, passos, entradas, resultados esperados, status, resultados encontrados, etc.

### Quando devemos fazer um Caso de Teste?
Casos de testes são feitos em diferentes situações

**Antes do desenvolvimento:** 
Pode ser escrito antes do código ser feito, isso ajuda a identificar os requisitos da aplicação/software e a realizar os testes mais tarde, quando o for desenvolvido.

**Depois do desenvolvimento:** 
Casos de testes também são feitos diretamente após a criação de uma aplicação/software ou após o desenvolvimento de um recurso.

**Durante o desenvolvimento:** 
Às vezes são feitos durante o tempo de desenvolvimento, em paralelo. Portanto, sempre que uma parte do módulo/software é desenvolvida, ela também é testada.

### Por que devemos fazer Casos de testes?
Casos de testes são um dos aspectos mais importantes da engenharia de software, pois definem como os testes serão realizados. Casos de testes são feitos por uma simples razão, para verificar se o software funciona ou não. 

Vejamos um exemplo de um caso de teste em uma página de login.
![Caso de teste login](https://github.com/felipeenge/Teste-de-software/assets/121561336/df110ffd-600d-433e-90f3-866775ab34dc)
O resultado do teste pode ser passou/bloqueado/falhou

# Cenário de teste:

Cenários de testes são criados para garantir que cada funcionalidade de uma aplicação/software esteja funcionando como esperado. São necessários para verificar o desempenho de todo o sistema na perspectiva dos usuários. Ao criá-los, os Qa’s precisam se colocar no lugar dos usuários para esclarecer quais cenários do mundo real o software terá de lidar quando for tornado público.

**Por que criar Cenários de Testes?**
Ajuda a garantir a cobertura completa dos testes.

**Como criar Cenários de Testes?**
1. Ler cuidadosamente a documentação, Business Requirement Specification (BRS), Software Requirement Specification (SRS), Functional Requirement Specification (FRS).
2. Isolar todos os requisitos e identificar quais possíveis ações do usuário precisa ser testado.
3. Enumerar cenários de teste que cubram todos os recursos possíveis do software.
4. Certifique-se de que esses cenários abranjam todos os fluxos de usuários e fluxos de negócios envolvidos na operação do software/aplicativo, etc.

Vejamos um exemplo de cenário de teste em uma página de cadastro de usuário:

![Cenário de testes cadastro usuário)](https://github.com/felipeenge/Teste-de-software/assets/121561336/694158c4-3648-42e1-8c0c-487cd398819a)
Fonte: https://front.serverest.dev/cadastrarusuarios

Exemplo de cenário de teste na página de login que fui utilizada acima:

![Cenário de testes](https://github.com/felipeenge/Teste-de-software/assets/121561336/df797b5b-f11d-4033-93da-ece19d7850f5)


# Diferenças entre Caso de teste e Cenário de teste:

Caso de teste | Cenário de teste
:---: | :---:|
Oferece informação detalhada sobre o que testar, as etapas necessárias para o teste e o resultado preciso esperado. | Apenas detalha informações sobre qual feature deve ser testada e a história associada com a feature.
Obrigatório manter QA's e desenvolvedores sincronizados. | Obrigatório para que os testadores saibam qual é sua tarefa em alto nível.
Consiste em ações individuais de baixo nível que os testadores devem realizar. | Consiste em informações de alto nível (geralmente de uma linha) sobre qual recurso deve ser testado.
É derivado de cenários de teste. | É derivado do documento de requisitos.
A criação de casos de teste é um esforço único, pois os casos de teste podem ser reutilizados, especialmente durante testes de regressão. | Os cenários de teste podem precisar ser alterados à medida que o software evolui para se alinhar aos recursos recentemente desenvolvidos.
Principalmente útil para orientar testadores individuais sobre como progredir em um determinado projeto. | Mais útil para reduzir a complexidade, listando tudo o que deve ser testado e ajudando os testadores a criar casos de teste para cada cenário.

# Bug Report:

O Bug Report é um documento que descreve um problema encontrado em um software. O objetivo do relatório é fornecer informações suficientes para que os desenvolvedores possam entender e corrigir o problema.

### Tipos de Bug:

**Funcional**:
O software não está funcionando corretamente.
Ex: Um link que está sendo redirecionado para outro local, um botão que não clica.

**Visual (UI):**
Um bug visual (UI), é um defeito na interface gráfica do usuário em um software ou aplicação. Esse tipo de bug pode causar problemas visuais ou funcionais que fazem a interface difícil ou impossível de usar.
Ex: Botão fora do lugar.

**Conteúdo:**
É Um erro em um site ou app que afeta a qualidade ou a precisão do conteúdo.
Ex: Link quebrado, conteúdo faltando, formatação incorreta, erros gramaticais, etc

**Desempenho:**
É um bug no software que impacta de forma negativa a velocidade, tempo de resposta ao clicar em algo.
Ex: lentidão ao carregar a página ou software.

**Sugestão:**
Uma melhoria que você tiver em mente, pode ser levada em consideração. 
Ex: Uma melhoria na UI, uma alteração na fonte, mover uma imagem ou texto de um lugar para outro, etc.

## Tópicos para Bug Report:

1. Passos para a reprodução
2. Resultado esperado
3. Resulta encontrado
4. Ambiente de teste
5. Prioridade
6. Tipo
7. Evidência

**Vejamos um exemplo abaixo:**

![bug report](https://github.com/felipeenge/Teste-de-software/assets/121561336/c7de0cf4-1a1d-4d36-9569-0aac36fe869a)

