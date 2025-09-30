---
title: Guía de Uso da Web de Sementeira
draft: true
date: "2025-09-30"
description: ""
tags: []
authors:
  - "sementeira"
---

> Este artigo está dirixido a colaboradores e membros de Sementeira con interese en contribuír ao proxecto engadindo materiais á súa [web](https://sementeira.maega.gal/).

A web https://sementeira.maega.gal/ está aloxada no repositorio de Github [GitHub - AntFi03/semweb](https://github.com/AntFi03/semweb). Nel están ademais dos contidos, toda a programación necesaria para facer que a web funcione. Para simplificar este proceso temos o repositorio de Github [GitHub - AntFi03/semweb-obsidian](https://github.com/AntFi03/semweb-obsidian) que está enlazado co anterior (os cambios sincronízanse automaticamente) e só contén o *contido* da web.

Desta forma, a través do software [Obsidian](https://obsidian.md/) que ten soporte de LaTeX (o mellor que coñezo, mellor que Overleaf, TexStudio...) e é un editor de ficheiros `.md` poderedes editar nos vosos equipos directamente o contido da web de xeito autónomo.

Neste documento explico cal é o procedemento paso por paso para instalar nos vosos equipos todo o necesario para poder editar a web e subir os vosos problemas logo de telos empregado nas sesións.

## Titorial para a Instalación do Sistema
Cabe sinalar que o procedemento apenas varía dun sistema operativo a outro, pero por limitacións persoais de tempo e xeneralidade de uso prioricei as indicacións para Windows.

### Windows
#### 1. Permisos e conta de GitHub
O primeiro paso é crear un conta de [GitHub](https://github.com/) (é unha plataforma moi moi coñecida onde a xente sube os seus códigos, e é onde temos funcionando as webs de MaEGA e Sementeira). Logo de tela creado, enviar unha solicitude ao [correo de Sementeira](mailto:sementeira.problemas@gmail.com) para que vos dé permisos de edición no repositorio [semweb-obsidian](https://github.com/AntFi03/semweb-obsidian). Unha vez que vos engada ao repositorio, teredes que aceptar a invitación mediante un correo que vos chegará ao voso correo electrónico. Ademais recibiredes por parte do administrador da web unha carpeta de configuracións de Obsidian que empregaremos máis adiante.

#### 2. Instalación de Obsidian
Imos á web de [Obsidian](https://obsidian.md/) e instalamos a versión para o noso sistema.

#### 3. Instalación de Git
Imos á web [Git - Downloads](https://git-scm.com/downloads) e instalamos a versión para o noso sistema.

#### 4. Creación da vosa web local
Obsidian funciona nun directorio, polo que tendes que elixir unha carpeta do voso ordenador na que vaiades a ter unha copia da web gardada. Vale calquera, mentres teñades espazo dabondo (<1Gb, moi pouco).

#### 5. Configuración Obsidian
Para saltarnos toda a configuración debedes posicionar a carpeta de configuración que obtivechedes no paso 1 dentro da carpeta que seleccionastes no paso 4. É posible que para ver esta carpeta no explorador debates activar a visión de cartafoles ocultos (os cartafoles que comezan un punto `.` chámanse ocultos).

#### 6. Configuración de Git
Esta é a parte sensible, imos configurar Git (xestor de paquetes que nos permite sincronizar os nosos cambios co repositorio [semweb-obsidian](https://github.com/AntFi03/semweb-obsidian)) para iso temos que abrir unha terminal con `Win+R` e escribindo `cmd`. Unha vez nela navegamos co comando `cd` ata a carpeta seleccionada no paso 4. Unha vez nela executamos as seguintes sentenzas:
```cmd
git config credential.helper
```
Debera de abrirse unha ventá na que poidamos indicar as credenciais da nosa conta de GitHub. Unha vez feito isto pasamos a clonar o noso repositorio:
```cmd
git clone https://github.com/AntFi03/semweb-obsidian.git
```
Reiniciamos obsidian. 

#### 7. Uso
Xa debera de estar todo disposto. Cada vez que se abra Obsidian sincronizaranse os cambios feitos por outros colaboradores, actualizando á última versión do repositorio (isto pode forzarse con `Alt+X`). Cando rematedes de facer os vosos cambios só tendes que subilos ben no botón de *commit+push* ou ben con `Alt+C`.