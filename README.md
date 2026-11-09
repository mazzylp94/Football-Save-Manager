# Football-Save-Manager
use any patch of any football videogame at the same time, tool easy to use, 1 click to play your patch.

# 🎮 Football Save Manager

## 🇬🇧 English

**Football Save Manager** is a free and portable application for Windows designed to manage savegames from multiple football games, patches, and seasons, including Pro Evolution Soccer (PES), FIFA, and other football titles.

Switch between different patches without losing your progress! The application automatically backs up and restores savegame files, keeping each patch's data organized and separate.

### Features
- Automatic savegame backup and restoration.
- Compatible with multiple PES, FIFA, and other football games.
- Manage different patches and seasons independently.
- Savegame identification to help prevent accidental overwriting.
- Support for multiple executables with customizable launch delays.
- Customizable savegame directories.
- Multilingual interface: English, Spanish, Portuguese, and community translations.
- Portable configuration and backups.
- Last played and last backup date records.
- No Python installation required when using the compiled executable.

---

## 🇦🇷 Español

**Football Save Manager** es una aplicación gratuita y portátil para Windows, diseñada para administrar partidas guardadas de diferentes juegos de fútbol, parches y temporadas, incluyendo Pro Evolution Soccer (PES), FIFA y otros títulos.

¡Cambiá entre distintos parches sin perder tu progreso! El programa permite realizar copias de seguridad y restaurar automáticamente las partidas guardadas, manteniendo los datos de cada parche organizados e independientes.

### Características
- Copias de seguridad y restauración automática de partidas.
- Compatible con múltiples versiones de PES, FIFA y otros juegos de fútbol.
- Administración independiente de parches y temporadas.
- Identificación de partidas para ayudar a evitar sobrescrituras accidentales.
- Soporte para múltiples ejecutables con intervalos de inicio configurables.
- Rutas de guardado personalizables.
- Interfaz multidioma: inglés, español, portugués y traducciones de la comunidad.
- Configuración y respaldos portátiles.
- Registro de fecha del último juego y último respaldo.
- No requiere instalar Python al utilizar el ejecutable compilado.

---

## 🇧🇷 Português

**Football Save Manager** é um aplicativo gratuito e portátil para Windows, desenvolvido para gerenciar arquivos de jogos salvos de diferentes jogos de futebol, patches e temporadas, incluindo Pro Evolution Soccer (PES), FIFA e outros títulos.

Alterne entre diferentes patches sem perder seu progresso! O programa permite fazer backups e restaurar automaticamente os arquivos salvos, mantendo os dados de cada patch organizados e separados.

### Funcionalidades
- Backup e restauração automática dos jogos salvos.
- Compatível com várias versões de PES, FIFA e outros jogos de futebol.
- Gerenciamento independente de patches e temporadas.
- Identificação dos arquivos salvos para ajudar a evitar substituições acidentais.
- Suporte a múltiplos executáveis com intervalos de inicialização configuráveis.
- Diretórios de arquivos salvos personalizáveis.
- Interface multilíngue: inglês, espanhol, português e traduções da comunidade.
- Configurações e backups portáteis.
- Registro da data da última execução e do último backup.
- Não requer instalação do Python ao utilizar o executável compilado.

---

# 📖 How to Use / Cómo usar / Como usar

## 🇬🇧 English — Basic Instructions

### 1. Add a new patch

Open **Football Save Manager** and click **Add**.

Enter the following information:

- **Game:** Enter the base game name (e.g., PES 6, PES 2013, PES 2021, FIFA 14).
- **Patch / Option File:** Enter the name of the patch, option file, or season you want to manage.
- **Save Folder:** Select the folder where the game stores its save files, usually inside your Documents folder.
- **Executables:** Add the executable files in the order they should launch, such as `sider.exe` first and `PES2021.exe` second. You can configure the delay between launches in Settings.

Save the new entry.

### 2. Add the Option File or saved games

When a new patch is created, Football Save Manager automatically creates an **empty backup folder**.

Click **View Folder** to open it and manually copy the patch's Option File or save files into it, if required.

**Important:** Preserve the original folder structure of the files.

For example, if the game requires:

`Documents\PES6\data\save\optionfile.dat`

And the configured save folder is `Documents\PES6`, place the file inside the backup folder as:

`data\save\optionfile.dat`

Do not place the file directly in the backup folder if it belongs inside subfolders.

### 3. Play

Select the game and patch you want to use, then click **Play**.

Football Save Manager will copy the selected patch's save files into the corresponding game save directory, launch the configured executables in order, and close automatically.

### 4. Automatic backup

When you reopen Football Save Manager, it can confirm the last patch you played (if the confirmation option is enabled).

The program then backs up the current save files to the corresponding patch's backup folder, preserving your latest progress.

**Important:** Football Save Manager remembers the last patch launched through the application. It cannot automatically know if you played another patch manually outside the manager.

If you used another patch outside the program, do not confirm that the remembered patch was the last one played. Otherwise, saves could be assigned to the wrong patch.

The program also uses a patch identification file to help recognize and back up the saves currently loaded when switching patches.

---

## 🇦🇷 Español — Instrucciones básicas

### 1. Agregar un nuevo parche

Abrí **Football Save Manager** y hacé clic en **Agregar**.

Completá los siguientes datos:

- **Juego:** Escribí el nombre del juego base (por ejemplo, PES 6, PES 2013, PES 2021 o FIFA 14).
- **Parche / Option File:** Indicá el nombre del parche, Option File o temporada que querés administrar.
- **Carpeta de guardado:** Seleccioná la carpeta donde el juego guarda sus partidas, generalmente dentro de Documentos.
- **Ejecutables:** Agregá los ejecutables en el orden en que deben iniciarse, por ejemplo, primero `sider.exe` y después `PES2021.exe`. El intervalo entre ejecuciones se puede modificar desde Configuración.

Guardá la nueva entrada.

### 2. Agregar el Option File o las partidas guardadas

Al crear un parche nuevo, Football Save Manager genera automáticamente una **carpeta de respaldo vacía**.

Presioná **Ver carpeta** (o **Inspeccionar**, según la versión) para abrirla y copiar manualmente los archivos del Option File o las partidas del parche, si corresponde.

**Importante:** Tenés que respetar la estructura original de las carpetas.

Por ejemplo, si el juego necesita el archivo en:

`Documentos\PES6\data\save\optionfile.dat`

Y configuraste como carpeta de guardado `Documentos\PES6`, dentro de la carpeta de respaldo deberás crear:

`data\save\optionfile.dat`

No copies el archivo suelto en la raíz del respaldo si originalmente pertenece a una subcarpeta.

### 3. Jugar

Seleccioná el juego y el parche que querés utilizar y presioná **Jugar**.

Football Save Manager copiará los archivos de guardado del parche seleccionado a la carpeta correspondiente, iniciará los ejecutables en el orden configurado y se cerrará automáticamente.

### 4. Copia de seguridad automática

Cuando vuelvas a abrir Football Save Manager, el programa podrá preguntarte si el último parche registrado fue realmente el último que jugaste, siempre que tengas activada esa opción.

Después realizará una copia de seguridad de las partidas actuales en la carpeta correspondiente, conservando tu progreso.

**Importante:** Football Save Manager recuerda el último parche iniciado desde el propio programa. No puede saber automáticamente si jugaste otro parche manualmente por fuera del administrador.

Si utilizaste otro parche sin abrirlo desde Football Save Manager, no confirmes que el parche recordado fue el último utilizado, porque podrías asignar las partidas al parche equivocado.

El programa también utiliza un archivo identificador para reconocer los saves cargados y ayudar a respaldarlos correctamente al cambiar de parche.

---

## 🇧🇷 Português — Instruções básicas

### 1. Adicionar um novo patch

Abra o **Football Save Manager** e clique em **Adicionar**.

Preencha as seguintes informações:

- **Jogo:** Digite o nome do jogo base (por exemplo, PES 6, PES 2013, PES 2021 ou FIFA 14).
- **Patch / Option File:** Informe o nome do patch, Option File ou temporada que deseja gerenciar.
- **Pasta de salvamento:** Selecione a pasta onde o jogo armazena os arquivos salvos, geralmente dentro da pasta Documentos.
- **Executáveis:** Adicione os arquivos executáveis na ordem em que devem iniciar, por exemplo, primeiro `sider.exe` e depois `PES2021.exe`. O intervalo entre as execuções pode ser ajustado nas Configurações.

Salve a nova entrada.

### 2. Adicionar o Option File ou os arquivos salvos

Ao criar um novo patch, o Football Save Manager cria automaticamente uma **pasta de backup vazia**.

Clique em **Ver pasta** (ou **Inspecionar**, dependendo da versão) para abri-la e copiar manualmente os arquivos do Option File ou os arquivos salvos do patch, quando necessário.

**Importante:** Preserve a estrutura original das pastas.

Por exemplo, se o jogo precisar do arquivo em:

`Documentos\PES6\data\save\optionfile.dat`

E a pasta de salvamento configurada for `Documentos\PES6`, dentro da pasta de backup você deverá criar:

`data\save\optionfile.dat`

Não coloque o arquivo diretamente na raiz do backup se ele pertence a uma subpasta.

### 3. Jogar

Selecione o jogo e o patch desejado e clique em **Jogar**.

O Football Save Manager copiará os arquivos salvos do patch selecionado para a pasta correspondente, iniciará os executáveis na ordem configurada e fechará automaticamente.

### 4. Backup automático

Ao abrir novamente o Football Save Manager, o programa poderá perguntar se o último patch registrado foi realmente o último utilizado, caso a opção de confirmação esteja ativada.

Em seguida, fará um backup dos arquivos salvos atuais na pasta correspondente, preservando seu progresso.

**Importante:** O Football Save Manager lembra o último patch iniciado pelo próprio aplicativo. Ele não consegue saber automaticamente se você jogou outro patch manualmente fora do gerenciador.

Se você utilizou outro patch sem iniciá-lo pelo Football Save Manager, não confirme que o patch registrado foi o último utilizado, pois os arquivos salvos poderão ser associados ao patch errado.

O programa também utiliza um arquivo de identificação para reconhecer os saves carregados e ajudar a fazer backups corretamente ao trocar de patch.

## 👨‍💻 Credits / Créditos

**Created by / Creado por / Criado por: MATI1313**

YouTube: https://www.youtube.com/@MATI_1313

### Distribution / Distribución / Distribuição

🇬🇧 This software is distributed free of charge. You may share it as long as you credit MATI1313 and mention the YouTube channel. **If you paid for this program, you have been scammed.**

🇦🇷 Este programa se distribuye gratuitamente. Podés compartirlo siempre que menciones a MATI1313 y su canal de YouTube. **Si pagaste por este programa, te estafaron.**

🇧🇷 Este programa é distribuído gratuitamente. Você pode compartilhá-lo desde que dê os créditos a MATI1313 e mencione seu canal no YouTube. **Se você pagou por este programa, foi enganado.**
