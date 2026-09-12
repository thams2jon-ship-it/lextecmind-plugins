# LexTecMind — plugins para o Claude Code

Catálogo de plugins da LexTecMind para o Direito Eleitoral.

Este repositório contém **apenas as fichas dos plugins** — os arquivos que dizem
ao Claude Code que o plugin existe e como iniciá-lo. O programa em si não está
aqui: ele é instalado à parte, na máquina de quem usa.

## MCP PJe

Dá ao Claude acesso aos dados e às peças processuais oficiais do PJe, com
rotinas programadas de análise e entrega das minutas no Google Drive ou em
pasta local. Funciona nos 27 tribunais regionais eleitorais, no 1º e no 2º grau.

**Exige chave de acesso.** A chave é fornecida na contratação e vale para um
computador. Sem ela, o plugin instala mas nenhuma ferramenta responde.

### Instalação

A instalação é feita na sessão de implantação, em dois passos:

1. **O programa**, com o instalador fornecido junto da chave de acesso.
2. **O plugin**, no Claude Code: *Configurações → Plugins → Adicionar*, e então
   o endereço deste repositório.

Na primeira pergunta sobre o PJe, abre uma janela pedindo a chave de acesso, o
tribunal, o CPF e a senha. Os dados ficam no cofre de credenciais do Windows,
na máquina de quem usa — nada é enviado para fora.

O manual completo acompanha a contratação.

### Suporte

Jonathan Gadelha · ia.jonathangam2@gmail.com · (81) 98125-2689

---

© LexTecMind. Software proprietário. A ficha publicada aqui não autoriza uso do
programa sem chave de acesso válida.
