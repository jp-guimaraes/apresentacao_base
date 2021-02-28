+++
weight = 3
+++

{{% section %}}

# Checklist

O que ter em mente e o que fazer antes e durante a instalação de um sistema operacional?

---

1. Qual sistema operacional vai ser instalado/reinstalado?
1. O backup já foi realizado?
1. Qual sistema operacional será instalado?
    - Hardware tem suporte a esse SO? (32 bits, 64 bits, drivers, plataforma)
1. Qual mídia será usada para instalação?
    - CD,DVD,pendrive, boot pela rede?
1. Hardware tem suporte a essa mídia?
1. Qual disco vai receber o sistema operacional?
    - Disco foi instalado?
    - Disco está sendo reconhecido pela BIOS do computador ou pelo sistema operacional antigo?
1. Qual partição do disco escolhido vai receber o sistema operacional?
    - Qual sistema de arquivo deve ser usado para o SO?
    - Conferir backup
    - Realizar formatação para sistema de arquivo apropriado (quando necessário)

---

# Procedimento

1. Fazer backup
1. Criar mídia bootável
    - CD, DVD, USB, Rede -> Vendedor ou software especialista para criação 
    - **recomendo RUFUS -> GPT, MBR**
1. Particionar e formatar o volume que vai receber o SO
    - **em caso de particionamento, recomendo o gparted**
1. No setup, colocar mídia escolhida como prioridade
1. Seguir passo a passo do instalador do sistema 
1. Conectar o computador a internet e baixar as últimas atualizações do sistema operacional e os **drivers**



{{% /section %}}




