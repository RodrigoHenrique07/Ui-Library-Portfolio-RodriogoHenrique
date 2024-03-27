# UI Library Rodrigo

A UI Library Rodrigo é uma biblioteca de componentes JavaScript que fornece uma variedade de elementos de interface do usuário prontos para uso. Esses componentes podem ser úteis para criar um portfólio web com base no design fornecido no projeto Figma [My Web Portfolio](<https://www.figma.com/file/vTMYqLqlfREJ1JREU2angJ/My-Web-Portfolio-(Community)?type=design&node-id=0-1&mode=design&t=BL8kARvFqxRKqYDn-0>).

# Padrão seguido na criação do pacote
 <ul> 
   <li>Vite</li>
   <li>React</li>
   <li>Typescript</li>
  <li>Typescript</li>
    <ul> 
   <li>ESLint</li>
   <li>Prettier</li>
   
 </ul>
 </ul>

  <ul> 
   <li>Storybook/li>
   <li>Rollup</li>
   
 </ul>

## Instalação para utilizar o pacote

Para instalar a biblioteca UI Library Rodrigo em seu projeto React com TypeScript, você pode usar o npm. Execute o seguinte comando no terminal:

```bash
npm i ui-library-portfoliorodrigo

```

Você pode usar os componentes diretamente no seu projeto React. Aqui está um exemplo de como você pode importar e usar os componentes:

import React from 'react';
import { ButtonContato, ButtonDown, Subtitle, TagsProjetos, Title, Topbar, TopicosTag, TrabalhosProjetosCards, TrajetoriaCard } from 'ui-library-rodrigo';

```
export function SectionProject() {
  return (
    <>
          <TopicosTag icon="🔗" texto=" Portfólio" />
          <Title texto="Trabalhos e projetos" />

              <TrabalhosProjetos
                titulo='Move it'
                text='lorem...'
                img={caminho imagem}
                url='http://localhost:3333/'
              >
                <TagsProjetos texto='HTML' />
                <TagsProjetos texto='JavaScript' />
              </TrabalhosProjetos>



    </>
  )
}
```
#
# Para clonar o projeto e editar os componentes:

```bash
    npm install --> para instalar as rependências do projeto
    npm run storybook --> visualizar os componentes no http://localhost:6006/
    npm run rollup --> gerar o build dos arquivos na pasta dist

```

# Publicar no npm seu proprio pacote:

```bash
    Criar uma conta no npm

    no terminal rodar o comando:
      npm login --> fazer a autenticação

    Noemar seu pacote:
      npm init --scope=nome_do_pacote

  Publicar no npm:

    npm publish


    
    
    

```


