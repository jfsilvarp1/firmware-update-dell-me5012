# Procedimento para atualizar o Dell Controller Storage ME5012

Storage STI: 10.0.0.170 - 171
SERVICE TAG: CYQLCW3

Storage CETIRP-STI: 10.0.0.172 - 173
SERVICE TAG: FYQLCW3

1) Acessar site Dell Suporte
    - https://www.dell.com/support/home/pt-br
    - inserir service tag
2) Verificar a disponibilidade de updates críticos, normalmente com o "ESSENCIAL" em vermelho na frente do update;
3) Baixar a atualização para o computador conectado ao Controller;
    Descompactar o arquivo baixado, caso esteja compactado;
4) Acessar o Controller para realizar o UPDATE:
    - https://10.0.0.172
        - manage
        - Poi.....@@
5) Navegar seguinto o caminho:
    No menu lateral da tela do Controller: Maintenance >> Firmware >> Browse File >> "Escolher o aquivo baixado e descompactado";

6) Ativando a versão:
    - A última versão instalada, também deverá ser ativada para ser a firmware ativa. Clicar em:  "Activate this Version"