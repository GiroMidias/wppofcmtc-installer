WPP OFC Mautic Installer
Instalador público do plugin WhatsApp Official for Mautic.

O que este repositório faz
baixa e executa o bootstrap de instalação
pede a URL da API de licença
valida a licença online
baixa o pacote privado assinado
instala o plugin no diretório do Mautic
O que este repositório não faz
não contém segredo do GitHub
não contém chave privada
não contém o código protegido do plugin
não acessa o repositório privado diretamente com credencial embutida
Estrutura
wppofcmtc-installer/
├─ install.sh
├─ update.sh
├─ uninstall.sh
├─ dist/
│  └─ lib/
│     └─ common.sh
└─ docs/
   └─ api-contract.md
Uso
bash -c "$(curl -fsSL https://raw.githubusercontent.com/GiroMidias/wppofcmtc-installer/main/install.sh)"
O script vai pedir:

URL da API
licença
caminho do Mautic
Observação importante
O pacote comercial é liberado pela API de licença com URL temporária e assinatura.
O instalador apenas baixa, valida e copia os arquivos.
