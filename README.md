# AtividadeEADWEB
# Meu Perfil Acadêmico 🎓

## 📝 Explicação do Código

### 1. Como você montou a estrutura básica do arquivo `index.html`? Explique a função de `<!DOCTYPE html>`, `<html>`, `<head>` e `<body>`.
A estrutura foi organizada seguindo o padrão fundamental do HTML5. A declaração `<!DOCTYPE html>` informa ao navegador que o documento está na versão HTML5, permitindo a renderização correta. A tag `<html>` engloba todo o conteúdo da página e define o idioma principal. Por fim, o `<head>` guarda as configurações e metadados que não aparecem na tela, enquanto o `<body>` contém os elementos visíveis para o usuário.

---

### 2. O que você colocou dentro do `<head>` e qual é a função de cada elemento utilizado?
Dentro da tag `<head>`, incluí a tag `<meta charset="UTF-8">` para garantir o suporte adequado a caracteres em português (como acentos e ç), e a `<meta name="viewport" content="width=device-width, initial-scale=1.0">` para adaptar a página a dispositivos móveis. Também utilizei a tag `<title>Meu perfil acadêmico</title>` para definir o título que aparece na aba do navegador. Por fim, adicionei a tag `<style>` onde declarei todas as regras CSS para estilizar a página.

---

### 3. Como você utilizou as duas `<div>` para separar e organizar os conteúdos da página? Informe também os nomes das classes criadas.
Utilizei as tags `<div>` como blocos contêineres para separar o conteúdo em duas seções bem definidas na página. Criei a classe `class="perfil"` para a primeira seção, reunindo a apresentação do Diego Tomaz, os parágrafos sobre sua formação e a lista de interesses. Para a segunda seção, utilizei a classe `class="objetivos"`, isolando o texto focado no aprendizado de Python, IA e análise de dados.

---

### 4. Como você aplicou o CSS dentro da tag `<style>`? Apresente um seletor, uma propriedade e um valor existentes no seu código.
Apliquei o CSS declarativo diretamente na tag `<style>` utilizando seletores para cada elemento ou classe que desejava estilizar. Como exemplo do meu código, utilizei o seletor `.perfil h2` com a propriedade `color` e o valor `#c30303` (cor vermelha). Isso define que os subtítulos das seções tenham um destaque bem chamativo.

---

### 5. Quais cores e propriedades visuais você escolheu e qual foi o resultado observado no navegador?
Escolhi uma paleta vibrante: fundo do `body` na cor roxa/azul `#424293`, título principal `h1` na cor clara `#f4f4f9`, subtítulos `h2` em vermelho `#c30303` e textos das divs na cor azul `#0014ef`. Nas divs `.perfil` e `.objetivos`, utilizei fundos claros (`#ffffff` e `#fefefe`), bordas estilizadas (`border: 2px solid #000000;` na primeira e `#f8f2f2` na segunda), além de `padding: 20px;` e `border-radius`. No navegador, o resultado foi uma página com forte contraste visual, destacando bem os blocos brancos sobre o fundo roxo e mantendo os textos perfeitamente legíveis.

---

### 6. Qual alteração ou correção foi necessária depois que você testou a página? Caso não tenha ocorrido erro, explique como realizou o teste.
O teste foi realizado salvando o código no arquivo `index.html` e executando o arquivo diretamente no navegador Google Chrome. Durante os testes visuais, verifiquei que o texto ficava colado nas bordas internas das caixas e que as cores precisavam de maior contraste para destacar as seções. Ajustei a propriedade `padding` para `20px` nas classes `.perfil` e `.objetivos`, além de personalizar os tons de vermelho, azul e o fundo roxo `#424293` para garantir uma estética personalizada e equilibrada.
