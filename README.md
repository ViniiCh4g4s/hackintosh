# ASUS Z490M-PLUS Hackintosh - OpenCore 0.6.4

<img src="https://user-images.githubusercontent.com/68537257/124525748-3997c980-ddb5-11eb-8ed6-6b3b07aeae73.png" />


# História

Esperamos que este repositório ajude outros que estão procurando fazer um hackintosh, especialmente se estiverem usando o mesmo hardware e tudo funciona exatamente como em um Mac real.

Sempre fui fã do sistema da Apple e já adquiri alguns macbooks de gerações passadas, porém eu queria algo que me desse desempenho e que não tivesse que gastar o olho da cara. Então, pesquisei o Clover nos fóruns do tonymac e, embora houvesse grandes construções e histórias de sucesso, eu queria uma máquina confiável e quase idêntica a um Mac. Avance rapidamente e aqui estamos nós, com Opencore 0,6...; Decidi pesquisar pesadamente hardware compatível, que funcionasse com meu orçamento (veja Hardware, abaixo).

Depois de incontáveis leituras do <a href="https://dortania.github.io/OpenCore-Install-Guide/">Guia de instalação do Open Core</a>, percorrendo Reddit <a href="https://www.reddit.com/r/hackintosh/">r/hackintosh</a> e acompanhando no canal <a href="https://www.youtube.com/channel/UCPCUdJ9cRior4FZ1TEz6qdA">Dicas do Mateus</a> (/r/Hackintosh Paradise), consegui encontrar maneiras de fazer minha máquina executar o sistema MacOS. Vou compartilhar para ajudar outras pessoas, para que não cometam os mesmos erros e, com sorte, economizem muito tempo e frustação.

# Especificações

### Hardware

+ Motherboard: ASUS Z490M-PLUS (Realtek® ALC887)
+ CPU: Intel i5 10400F 2.90GHz (4.30GHz Turbo)
+ GPU: Radeon, RX 550 Red Dragon, 4GB, DDR5, 128Bit, AXRX 550 4GBD5-DH
+ CPU Cooler: Water Cooler Rise Mode Gamer Black, RGB, 240mm - RM-WCB-02-RGB
+ RAM: Hyperx DDR4 8GB (1x 8GB) 2666MHz
+ NVMe: PNY CS2130, 500GB, M.2 NVMe (MacOS)
+ SSD: Kingston A400 480GB (Win10)
+ PSU: KCAS 500W 59765
+ Case: Gabinete Gamer T-Dagger G25B TGC-G25B
+ Placa de WiFi/BT PCIExpress (Compatível com Hackintosh): <a href="https://pt.aliexpress.com/item/33034394024.html?aff_fcid=4e6e9ef04cd943118b61bb0cece43713-1625532523670-06798-_dUZ8uWx&aff_fsk=_dUZ8uWx&aff_platform=portals-tool&sk=_dUZ8uWx&aff_trace_key=4e6e9ef04cd943118b61bb0cece43713-1625532523670-06798-_dUZ8uWx&terminal_id=aae324a055694c0099f712dec52ec68f&tmLog=new_Detail">FV-HB1200</a>
+ Keyboard: Logitech K235
+ Mouse: Logitech M170
+ Monitor: LG LED 29´ Ultrawide - 29WK600

### Drivers

+ AudioDxe.efi (post-install)
+ HfsPlus.efi
+ OpenCanopy.efi (post-install)
+ OpenRuntime.efi

### Kexts

+ AppleALC.kext
+ IntelMausiEthernet.kext
+ Lilu.kext
+ NVMeFix.kext
+ SMCProcessor.kext
+ SMCSuperIO.kext
+ VirtualSMC.kext
+ WhateverGreen.kext

### SDDTs

+ SDDT-AWAC.aml
+ SDDT-EC.aml
+ SDDT-PLUG.aml
+ SDDT-USB-Reset.aml
+ SDDT-USBX.aml

### SMBIOS

iMac 20,2![Captura de Tela 2021-07-05 às 17 53 56](https://user-images.githubusercontent.com/68537257/124527237-fa1fac00-ddb9-11eb-917d-5fb1a150febf.png)

### O que está funcionando

Tudo o que testei até agora. Isso inclui:

Áudio
WiFi
Bluetooth
Opencore Bootloader
Entradas USB

### O que não está funcionando

Nada que eu tenha encontrado.


### Testes

<table>
  <tr>
    <td><a href="https://user-images.githubusercontent.com/68537257/124527537-ae213700-ddba-11eb-8d5e-288f25952cd8.png"><a/></td>
  <tr>
    <tr>
    <td>PHP</td>
  <tr>
</table>

    



