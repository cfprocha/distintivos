## Como criar Distintivos para o Github?

O processo é muito simples e vou ensiná-lo passo-a-passo aqui:

1. Localize o logotipo que deseja usar no seu distintivo, através do site [Simple Icons](https://simpleicons.org/)

2. Monte a URL para o distintivo, da seguinte forma:

    a) Comece com esse trecho de URL: https[]()://img.shields.io/badge    
        Sim, vamos usar o site [shields.io](https://img.shields.io/badge) para a criação

    b) Agora adicione o texto que deseja escrito no distintivo. Inicie com um hífen, para deixar um espaço entre o escudo e o texto e se for um texto composto (duas ou mais palavras) use um sublinhado ou o %20 para separar elas. 
    
    Exs.: https[]()://img.shields.io/badge/-vs_code<br/>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
          https[]()://img.shields.io/badge/-vs%20code

    c) Defina a cor que deseja no fundo do seu distintivo. Recomendo que use a cor indicada no próprio site do Simple Icons. Só atente que no site ele indica o código hex da cor, colocando um # na frente dos números e aqui precisamos apenas dos números. A cor deve ser informada inserindo um hífen após o texto do distintivo, conforme demonstrado abaixo.<br/><br/>
    https[]()://img.shields.io/badge/-vs_code-007ACC

    d) Então chegamos no momento de adicionar o logotipo, para isso, insira no URL o texto **?logo=** seguido pelo nome indicado no site Simples Icons (em letras minúsculas). Repare que se for um nome composto, deve ser usado hífen no lugar dos espaços, conforme exemplo abaixo.<br/><br/>
    https[]()://img.shields.io/badge/-vs_code-007ACC?logo=visual-studio-code<br/><br/>
    *Caso não esteja disponível um logotipo para o seu distintivo, basta pular essa etapa, que, simplesmente, será inserido um distintivo sem logotipo. Mas siga todas etapas seguintes

    e) Nesse momento deve ser definida a cor do logotipo e do texto. Sugiro que use sempre branco, para um melhor contraste com o fundo. A definição da cor é feita inserindo no URL a expressão **&logoColor=**. Para usar branco, simplesmente insira **white**, conforme exemplo abaixo.<br/><br/>
    https[]()://img.shields.io/badge/-vs_code-007ACC?logo=visual-studio-code&logoColor=white

    f) Para evitar que fique com distintivos de alturas diferentes, adicione uma outra propriedade para padronizar, que é **&style=for-the-badge**, conforme exemplo abaixo.<br/><br/>
    https[]()://img.shields.io/badge/-vs_code-007ACC?logo=visual-studio-code&logoColor=white&style=for-the-badge

    g) Isso já é o suficiente, mas se desejar padronizar ainda mais, pode usar qualquer uma das propriedades abaixo, lembrando sempre de adicionar um **&** antes de informar cada propriedade.
    **style=flat
    style=plastic
    style=flat-square
    logoWidth=** (aqui informe uma quantidade de pixels)

3. Agora incorpore essa URL ao seu readme.md usando a tag IMG do HTML, conforme demonstrado abaixo:

    \<img alt="VS Code" src="https[]()://img.shields.io/badge/-vs_code-007ACC?logo=visual-studio-code&logoColor=white&style=for-the-badge" /\>

    Não esqueça do atributo **alt** para garantir que seja apresentado um texto para usuários que não tenham como visualizar a imagem

## Exemplos

### Formas de Contato

|Distintivo |Código |
--- |--- |
<img alt="Outlook" src="https://img.shields.io/badge/Microsoft_Outlook-0078D4?logo=microsoft-outlook&logoColor=white&style=for-the-badge" />|`https://img.shields.io/badge/Microsoft_Outlook-0078D4?logo=microsoft-outlook&logoColor=white&style=for-the-badge`|
<img alt="Thunderbird" src="https://img.shields.io/badge/Thunderbird-0A84FF?logo=thunderbird&logoColor=white&style=for-the-badge" />|`https://img.shields.io/badge/Thunderbird-0A84FF?logo=thunderbird&logoColor=white&style=for-the-badge`|
<img alt="Gmail" src="https://img.shields.io/badge/Gmail-EA4335?logo=gmail&logoColor=white&style=for-the-badge" />|`https://img.shields.io/badge/Gmail-EA4335?logo=gmail&logoColor=white&style=for-the-badge`|
<img alt="Telegram" src="https://img.shields.io/badge/Telegram-2CA5E0?logo=telegram&logoColor=white&style=for-the-badge" />|`https://img.shields.io/badge/Telegram-2CA5E0?logo=telegram&logoColor=white&style=for-the-badge`|
<img alt="WhatsApp" src="https://img.shields.io/badge/WhatsApp-25D366?logo=whatsapp&logoColor=white&style=for-the-badge" />|`https://img.shields.io/badge/WhatsApp-25D366?logo=whatsapp&logoColor=white&style=for-the-badge`|
<img alt="Messenger" src="https://img.shields.io/badge/Messenger-00B2FF?logo=messenger&logoColor=white&style=for-the-badge" />|`https://img.shields.io/badge/Messenger-00B2FF?logo=messenger&logoColor=white&style=for-the-badge`|
<img alt="Discord" src="https://img.shields.io/badge/Discord-5865F2?logo=discord&logoColor=white&style=for-the-badge" />|`https://img.shields.io/badge/Discord-5865F2?logo=discord&logoColor=white&style=for-the-badge`|
<img alt="Line" src="https://img.shields.io/badge/Line-00C300?logo=line&logoColor=white&style=for-the-badge" />|`https://img.shields.io/badge/Line-00C300?logo=line&logoColor=white&style=for-the-badge`|
<img alt="Twitter" src="https://img.shields.io/badge/Twitter-1DA1F2?logo=twitter&logoColor=white&style=for-the-badge" />|`https://img.shields.io/badge/Twitter-1DA1F2?logo=twitter&logoColor=white&style=for-the-badge`|
<img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-0A66C2?logo=linkedin&logoColor=white&style=for-the-badge" />|`https://img.shields.io/badge/LinkedIn-0A66C2?logo=linkedin&logoColor=white&style=for-the-badge`|
<img alt="Facebook" src="https://img.shields.io/badge/Facebook-1877F2?logo=facebook&logoColor=white&style=for-the-badge" />|`https://img.shields.io/badge/Facebook-1877F2?logo=facebook&logoColor=white&style=for-the-badge`|
<img alt="Instagram" src="https://img.shields.io/badge/Instagram-E4405F?logo=instagram&logoColor=white&style=for-the-badge" />|`https://img.shields.io/badge/Instagram-E4405F?logo=instagram&logoColor=white&style=for-the-badge`|
<img alt="YouTube" src="https://img.shields.io/badge/YouTube-FF0000?logo=youtube&logoColor=white&style=for-the-badge" />|`https://img.shields.io/badge/YouTube-FF0000?logo=youtube&logoColor=white&style=for-the-badge`|
<img alt="Pinterest" src="https://img.shields.io/badge/Pinterest-BD081C?logo=pinterest&logoColor=white&style=for-the-badge" />|`https://img.shields.io/badge/Pinterest-BD081C?logo=pinterest&logoColor=white&style=for-the-badge`|
<img alt="TikTok" src="https://img.shields.io/badge/TikTok-000000?logo=tiktok&logoColor=white&style=for-the-badge" />|`https://img.shields.io/badge/TikTok-000000?logo=tiktok&logoColor=white&style=for-the-badge`|

### IDEs

|Distintivo |Código |
--- |--- |
<img alt="VS Code" src="https://img.shields.io/badge/VS_Code-007ACC?logo=visual-studio-code&logoColor=white&style=for-the-badge" />|`https://img.shields.io/badge/VS_Code-007ACC?logo=visual-studio-code&logoColor=white&style=for-the-badge`|
<img alt="IntelliJ IDEA" src="https://img.shields.io/badge/IntelliJ-20232A?logo=intellij-idea&logoColor=white&style=for-the-badge" />|`https://img.shields.io/badge/IntelliJ-20232A?logo=intellij-idea&logoColor=white&style=for-the-badge`|
<img alt="PHP Storm" src="https://img.shields.io/badge/-PHP%20Storm-20232A?logo=phpstorm&logoColor=white&style=for-the-badge" />|`https://img.shields.io/badge/-PHP%20Storm-20232A?logo=phpstorm&logoColor=white&style=for-the-badge`|
<img alt="Dream Weaver" src="https://img.shields.io/badge/-adobe_dreamweaver-FF61F6?logo=adobe-dreamweaver&logoColor=white&style=for-the-badge" />|`https://img.shields.io/badge/-adobe_dreamweaver-FF61F6?logo=adobe-dreamweaver&logoColor=white&style=for-the-badge`|

### Habilidades

|Distintivo |Código |
--- |--- |
<img alt="C" src="https://img.shields.io/badge/C-00599C?logo=c&logoColor=white&style=for-the-badge" />|`https://img.shields.io/badge/C-00599C?logo=c&logoColor=white&style=for-the-badge`|
<img alt="C#" src="https://img.shields.io/badge/C%23-239120?logo=c-sharp&logoColor=white&style=for-the-badge" />|`https://img.shields.io/badge/C%23-239120?logo=c-sharp&logoColor=white&style=for-the-badge`|
<img alt="HTML5" src="https://img.shields.io/badge/HTML-239120?logo=html5&logoColor=white&style=for-the-badge" />|`https://img.shields.io/badge/HTML-239120?logo=html5&logoColor=white&style=for-the-badge`|
<img alt="CSS3" src="https://img.shields.io/badge/CSS-239120?logo=css3&logoColor=white&style=for-the-badge" />|`https://img.shields.io/badge/CSS-239120?logo=css3&logoColor=white&style=for-the-badge`|
<img alt=".NET" src="https://img.shields.io/badge/.NET-5C2D91?logo=.net&logoColor=white&style=for-the-badge" />|`https://img.shields.io/badge/.NET-5C2D91?logo=.net&logoColor=white&style=for-the-badge`|
<img alt="ECMAScript" src="https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black&style=for-the-badge" />|`https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black&style=for-the-badge`|
<img alt="NodeJS" src="https://img.shields.io/badge/Node.js-43853D?logo=node.js&logoColor=white&style=for-the-badge" />|`https://img.shields.io/badge/Node.js-43853D?logo=node.js&logoColor=white&style=for-the-badge`|
<img alt="TypeScript" src="https://img.shields.io/badge/TypeScript-007ACC?logo=typescript&logoColor=white&style=for-the-badge" />|`https://img.shields.io/badge/TypeScript-007ACC?logo=typescript&logoColor=white&style=for-the-badge`|
<img alt="Sass" src="https://img.shields.io/badge/Sass-CC6699?logo=sass&logoColor=white&style=for-the-badge" />|`https://img.shields.io/badge/Sass-CC6699?logo=sass&logoColor=white&style=for-the-badge`|
<img alt="ExpressJS" src="https://img.shields.io/badge/Express.js-404D59?style=for-the-badge" />|`https://img.shields.io/badge/Express.js-404D59?style=for-the-badge`|
<img alt="React" src="https://img.shields.io/badge/React-20232A?logo=react&logoColor=61DAFB&style=for-the-badge" />|`https://img.shields.io/badge/React-20232A?logo=react&logoColor=61DAFB&style=for-the-badge`|
<img alt="Bootstrap" src="https://img.shields.io/badge/Bootstrap-563D7C?logo=bootstrap&logoColor=white&style=for-the-badge" />|`https://img.shields.io/badge/Bootstrap-563D7C?logo=bootstrap&logoColor=white&style=for-the-badge`|
<img alt="Material-UI" src="https://img.shields.io/badge/Material_UI-007FFF?logo=mui&logoColor=white&style=for-the-badge" />|`https://img.shields.io/badge/Material_UI-007FFF?logo=mui&logoColor=white&style=for-the-badge`|
<img alt="Redux" src="https://img.shields.io/badge/Redux-593D88?logo=redux&logoColor=white&style=for-the-badge" />|`https://img.shields.io/badge/Redux-593D88?logo=redux&logoColor=white&style=for-the-badge`|
<img alt="PHP" src="https://img.shields.io/badge/PHP-777BB4?logo=php&logoColor=white&style=for-the-badge" />|`https://img.shields.io/badge/PHP-777BB4?logo=php&logoColor=white&style=for-the-badge`|
<img alt="PHP myAdmin" src="https://img.shields.io/badge/-PHP%20myAdmin-6C78AF?logo=phpmyadmin&logoColor=white&style=for-the-badge" />|`https://img.shields.io/badge/-PHP%20myAdmin-6C78AF?logo=phpmyadmin&logoColor=white&style=for-the-badge`|
<img alt="R" src="https://img.shields.io/badge/R-276DC3?logo=r&logoColor=white&style=for-the-badge" />|`https://img.shields.io/badge/R-276DC3?logo=r&logoColor=white&style=for-the-badge`|
<img alt="Python" src="https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white&style=for-the-badge" />|`https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white&style=for-the-badge`|
<img alt="Markdown" src="https://img.shields.io/badge/Markdown-000000?logo=markdown&logoColor=white&style=for-the-badge" />|`https://img.shields.io/badge/Markdown-000000?logo=markdown&logoColor=white&style=for-the-badge`|
<img alt="Shell Script" src="https://img.shields.io/badge/Shell_Script-121011?logo=gnu-bash&logoColor=white&style=for-the-badge" />|`https://img.shields.io/badge/Shell_Script-121011?logo=gnu-bash&logoColor=white&style=for-the-badge`|
<img alt="mySQL" src="https://img.shields.io/badge/MySQL-20232A?logo=mysql&logoColor=white&style=for-the-badge" />|`https://img.shields.io/badge/MySQL-20232A?logo=mysql&logoColor=white&style=for-the-badge`|
<img alt="mariaDB" src="https://img.shields.io/badge/MariaDB-01529E?logo=mariadb&logoColor=white&style=for-the-badge" />|`https://img.shields.io/badge/MariaDB-01529E?logo=mariadb&logoColor=white&style=for-the-badge`|
<img alt="PostgreSQL" src="https://img.shields.io/badge/PostgreSQL-316192?logo=postgresql&logoColor=white&style=for-the-badge" />|`https://img.shields.io/badge/PostgreSQL-316192?logo=postgresql&logoColor=white&style=for-the-badge`|
<img alt="MongoDB" src="https://img.shields.io/badge/MongoDB-4EA94B?logo=mongodb&logoColor=white&style=for-the-badge" />|`https://img.shields.io/badge/MongoDB-4EA94B?logo=mongodb&logoColor=white&style=for-the-badge`|
<img alt="SQLite" src="https://img.shields.io/badge/SQLite-07405E?logo=sqlite&logoColor=white&style=for-the-badge" />|`https://img.shields.io/badge/SQLite-07405E?logo=sqlite&logoColor=white&style=for-the-badge`|
<img alt="MS SQL Server" src="https://img.shields.io/badge/Microsoft_SQL_Server-CC2927?logo=microsoft-sql-server&logoColor=white&style=for-the-badge" />|`https://img.shields.io/badge/Microsoft_SQL_Server-CC2927?logo=microsoft-sql-server&logoColor=white&style=for-the-badge`|
<img alt="Oracle Database" src="https://img.shields.io/badge/-Oracle%20Database-F80000?logo=oracle&logoColor=white&style=for-the-badge" />|`https://img.shields.io/badge/-Oracle%20Database-F80000?logo=oracle&logoColor=white&style=for-the-badge`|
<img alt="Redis" src="https://img.shields.io/badge/Redis-D9281A?logo=redis&logoColor=white&style=for-the-badge" />|`https://img.shields.io/badge/Redis-D9281A?logo=redis&logoColor=white&style=for-the-badge`|
<img alt="Azure" src="https://img.shields.io/badge/Microsoft_Azure-0089D6?logo=microsoft-azure&logoColor=white&style=for-the-badge" />|`https://img.shields.io/badge/Microsoft_Azure-0089D6?logo=microsoft-azure&logoColor=white&style=for-the-badge`|
<img alt="Excel" src="https://img.shields.io/badge/Microsoft_Excel-217346?logo=microsoft-excel&logoColor=white&style=for-the-badge" />|`https://img.shields.io/badge/Microsoft_Excel-217346?logo=microsoft-excel&logoColor=white&style=for-the-badge`|
<img alt="PowerPoint" src="https://img.shields.io/badge/Microsoft_PowerPoint-B7472A?logo=microsoft-powerpoint&logoColor=white&style=for-the-badge" />|`https://img.shields.io/badge/Microsoft_PowerPoint-B7472A?logo=microsoft-powerpoint&logoColor=white&style=for-the-badge`|
<img alt="Word" src="https://img.shields.io/badge/Microsoft_Word-2B579A?logo=microsoft-word&logoColor=white&style=for-the-badge" />|`https://img.shields.io/badge/Microsoft_Word-2B579A?logo=microsoft-word&logoColor=white&style=for-the-badge`|
<img alt="Outlook" src="https://img.shields.io/badge/Microsoft_Outlook-0078D4?logo=microsoft-outlook&logoColor=white&style=for-the-badge" />|`https://img.shields.io/badge/Microsoft_Outlook-0078D4?logo=microsoft-outlook&logoColor=white&style=for-the-badge`|
<img alt="Access" src="https://img.shields.io/badge/Microsoft_Access-A4373A?logo=microsoft-access&logoColor=white&style=for-the-badge" />|`https://img.shields.io/badge/Microsoft_Access-A4373A?logo=microsoft-access&logoColor=white&style=for-the-badge`|
<img alt="Visio" src="https://img.shields.io/badge/Microsoft_Visio-3955A3?logo=microsoft-visio&logoColor=white&style=for-the-badge" />|`https://img.shields.io/badge/Microsoft_Visio-3955A3?logo=microsoft-visio&logoColor=white&style=for-the-badge`|
<img alt="OneNote" src="https://img.shields.io/badge/-onenote-7719AA?logo=microsoft-onenote&logoColor=white&style=for-the-badge" />|`https://img.shields.io/badge/-onenote-7719AA?logo=microsoft-onenote&logoColor=white&style=for-the-badge`|
<img alt="O365" src="https://img.shields.io/badge/Office_365-D83B01?logo=microsoft-office&logoColor=white&style=for-the-badge" />|`https://img.shields.io/badge/Office_365-D83B01?logo=microsoft-office&logoColor=white&style=for-the-badge`|
<img alt="SharePoint" src="https://img.shields.io/badge/Microsoft_SharePoint-0078D4?logo=microsoft-sharepoint&logoColor=white&style=for-the-badge" />|`https://img.shields.io/badge/Microsoft_SharePoint-0078D4?logo=microsoft-sharepoint&logoColor=white&style=for-the-badge`|
<img alt="Apache" src="https://img.shields.io/badge/Apache-CA2136?logo=apache&logoColor=white&style=for-the-badge" />|`https://img.shields.io/badge/Apache-CA2136?logo=apache&logoColor=white&style=for-the-badge`|
<img alt="NGINX" src="https://img.shields.io/badge/Nginx-009639?logo=nginx&logoColor=white&style=for-the-badge" />|`https://img.shields.io/badge/Nginx-009639?logo=nginx&logoColor=white&style=for-the-badge`|
<img alt="Docker" src="https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white&style=for-the-badge" />|`https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white&style=for-the-badge`|
<img alt="VirtualBox" src="https://img.shields.io/badge/VirtualBox-183A61?logo=virtualbox&logoColor=white&style=for-the-badge" />|`https://img.shields.io/badge/VirtualBox-183A61?logo=virtualbox&logoColor=white&style=for-the-badge`|
<img alt="QEMU" src="https://img.shields.io/badge/QEMU-FF6600?logo=qemu&logoColor=white&style=for-the-badge" />|`https://img.shields.io/badge/QEMU-FF6600?logo=qemu&logoColor=white&style=for-the-badge`|
<img alt="VMWare" src="https://img.shields.io/badge/-VMWare-607078?logo=vmware&logoColor=white&style=for-the-badge" />|`https://img.shields.io/badge/-VMWare-607078?logo=vmware&logoColor=white&style=for-the-badge`|
<img alt="Proxmox" src="https://img.shields.io/badge/-Proxmox-E57000?logo=proxmox&logoColor=white&style=for-the-badge" />|`https://img.shields.io/badge/-Proxmox-E57000?logo=proxmox&logoColor=white&style=for-the-badge`|
<img alt="Hyper-V" src="https://img.shields.io/badge/-Hyper_V-017AD7?logoColor=white&style=for-the-badge" />|`https://img.shields.io/badge/-Hyper_V-017AD7?logoColor=white&style=for-the-badge`|
<img alt="Git" src="https://img.shields.io/badge/Git-E34F26?logo=git&logoColor=white&style=for-the-badge" />|`https://img.shields.io/badge/Git-E34F26?logo=git&logoColor=white&style=for-the-badge`|
<img alt="Windows" src="https://img.shields.io/badge/Windows-017AD7?logo=windows&logoColor=white&style=for-the-badge" />|`https://img.shields.io/badge/Windows-017AD7?logo=windows&logoColor=white&style=for-the-badge`|
<img alt="Linux" src="https://img.shields.io/badge/Linux-E34F26?logo=linux&logoColor=black&style=for-the-badge" />|`https://img.shields.io/badge/Linux-E34F26?logo=linux&logoColor=black&style=for-the-badge`|
<img alt="Mac OS" src="https://img.shields.io/badge/Mac_OS-20232A?logo=apple&logoColor=white&style=for-the-badge" />|`https://img.shields.io/badge/Mac_OS-20232A?logo=apple&logoColor=white&style=for-the-badge`|
<img alt="Digital Ocean" src="https://img.shields.io/badge/Digital Ocean-navy?logo=digitalocean&logoColor=white&style=for-the-badge" />|`https://img.shields.io/badge/Digital Ocean-navy?logo=digitalocean&logoColor=white&style=for-the-badge`|
<img alt="Vultr" src="https://img.shields.io/badge/Vultr-007BFC?logo=vultr&logoColor=white&style=for-the-badge" />|`https://img.shields.io/badge/Vultr-007BFC?logo=vultr&logoColor=white&style=for-the-badge`|
<img alt="WordPress" src="https://img.shields.io/badge/WordPress-21759B?logo=wordpress&logoColor=white&style=for-the-badge" />|`https://img.shields.io/badge/WordPress-21759B?logo=wordpress&logoColor=white&style=for-the-badge`|
<img alt="Woo Commerce" src="https://img.shields.io/badge/Woo_Commerce-96588A?logo=woo&logoColor=white&style=for-the-badge" />|`https://img.shields.io/badge/Woo_Commerce-96588A?logo=woo&logoColor=white&style=for-the-badge`|
<img alt="Moodle" src="https://img.shields.io/badge/Moodle-0F9D58?logo=google-classroom&logoColor=white&style=for-the-badge" />|`https://img.shields.io/badge/Moodle-0F9D58?logo=google-classroom&logoColor=white&style=for-the-badge`|
<img alt="Google Classroom" src="https://img.shields.io/badge/Google_ClassRoom-0F9D58?logo=google-classroom&logoColor=white&style=for-the-badge" />|`https://img.shields.io/badge/Google_ClassRoom-0F9D58?logo=google-classroom&logoColor=white&style=for-the-badge`|
<img alt="Zoom" src="https://img.shields.io/badge/Zoom-2D8CFF?logo=zoom&logoColor=white&style=for-the-badge" />|`https://img.shields.io/badge/Zoom-2D8CFF?logo=zoom&logoColor=white&style=for-the-badge`|
<img alt="Meet" src="https://img.shields.io/badge/Meet-00897B?logo=google-meet&logoColor=white&style=for-the-badge" />|`https://img.shields.io/badge/Meet-00897B?logo=google-meet&logoColor=white&style=for-the-badge`|
<img alt="Teams" src="https://img.shields.io/badge/Teams-6264A7?logo=microsoft-teams&logoColor=white&style=for-the-badge" />|`https://img.shields.io/badge/Teams-6264A7?logo=microsoft-teams&logoColor=white&style=for-the-badge`|
