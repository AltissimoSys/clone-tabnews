# Treinamento web - curso.dev
## Filipe Deschamps


## Git

[GitHub Felipe Deschamps](https://github.com/filipedeschamps)

### Codespaces:

[Aula Codespaces](https://curso.dev/web/ambiente-de-desenvolvimento-codespaces)

O Codespaces é um ambiente de desenvolvimento completo fornecido de forma gratuita pelo GitHub



---

### Docker

### No Windows existem três maneiras de se instalar e usar o Docker:
- Docker Desktop com a base no Hyper-V;
- Docker Desktop com a base no WSL;
- Docker Engine diretamente dentro do WSL;

O **_Docker Engine_** é o núcleo da ferramenta e o responsável pelo trabalho de criação, execução, e gerenciamento dos **_contêineres_**. É o motor que faz as coisas se mexerem. Por isso o nome "engine". Já o **_Docker Desktop_** é uma solução mais completa, que inclui **_o Docker Engine_**, mas oferece também uma interface gráfica para facilitar as configurações.

---

### Ubuntu Linux

**APT:** o gerenciador de pacotes do Ubuntu.

---

### NVM - Node Version Manager
Gerenciador de versões do NodeJs.
#### Anotações:
- Comando `nvm alias default` serve para setar a versão padrão do NodeJs no Shell (vale para o Codespaces).
- Para informarmos a versão do NodeJs usada no nosso projeto, criamos o arquivo `.nvmrc` na raiz do projeto (diretório **_\clone-tabnews_**), com a versão utilizada, no nosso caso **_lts/Hydrogen_**.

---

### Configuração do ambiente

Aqui será instalado o Git, Docker, NVM, NodeJs e todas as dependências.

[Aula configuração ambiente Windows](https://curso.dev/web/ambiente-de-desenvolvimento-windows)


--- 

### Next.js

[Link da aula](https://curso.dev/web/nextjs)

[Site do Next.js](https://nextjs.org/)
[Site da empresa por trás do Next.js - Vercel](https://vercel.com/)
[Diferença entre Node.js e Next.js](Docs/Diferenca_NodeJS_NextJS.docx)

**Resumo:**
- Node.js é a base: ele permite que o JavaScript rode no servidor.
- Next.js é construído em cima dessa base: ele usa Node.js para oferecer recursos avançados de desenvolvimento web com React.

#### Anotações:
- **Next.js:** uma das melhores integrações Framework/Web Host - A Vercel disponibiliza hospedagem gratuita que atende em muitos casos.

--- 

### Anotações Gerais:
- **Arquivo Manifesto:** criado como package.json, é onde ficarão listadas as verões dasd dpendências. 
**Para criar:**
    + executar `npm init`
    + Enter para todas as perguntas, exceto _license_ que deve ser igual a **_MIT_**   


- **Instação Next.js:**
    + Comando npm `install next@13.1.6` (13.1.6 é a versão que queremos instalar)  

- **Instação React:**
    + Comando `npm install react@18.2.0` (18.2.0 é a versão que queremos instalar)  


- **Desinstalar Node.Js e dependências:**
    + Comando `rm -rf node_modules package-lock.json` 



**Diferença entre .nvmrc e package.json:**   

   + `.nvmrc`: É usado exclusivamente pelo `NVM` para definir a versão do Node.js do projeto. Quando você roda nvm install, o `NVM` lê esse arquivo e instala a versão especificada.

   + `package.json`: É usado pelo `NPM` e lista informações importantes sobre o projeto, sendo a mais importante as dependências (módulos como `React`, `Next`, etc.) e suas versões.

   + Embora o `package.json` também permita especificar a versão do `Node` (na propriedade engines), nós não temos a conveniência do `NVM` conseguir ler esse arquivo automaticamente. Por isso usamos os dois.

---

# Dia 4




Depois que executei `npm run dev`, retornou para mim:
```bash
> clone-tabnews@1.0.0 dev
> next dev
error - Project directory could not be found, restart Next.js in your new directory
fabricio@DESKTOP-A8VBB56:/mnt/d/Estudos/web-curso.dev-deschamps/clone-tabnews$ 
```







--- 
Em 18/02/2026
# **[Parei nessa aula - em 18/02 ](https://curso.dev/web/npm-run-dev)**










---

Icons by [icons8](https://icons8.com.br/)