---
description: >-
  Página que descreve o passo a passo para vinculação do ponto base de projeto
  para todas as disciplinas.
cover: ../../.gitbook/assets/REVIT-POINTS.png
coverY: 0
layout:
  cover:
    visible: true
    size: hero
  title:
    visible: true
  description:
    visible: true
  tableOfContents:
    visible: true
  outline:
    visible: true
  pagination:
    visible: true
---

# 🌎 Revit: Vinculação de Projetos

### 1. INTRODUÇÃO

A vinculação é o processo que permite a compatibilização de projetos e que envolve todas as disciplinas de forma integrada. Como suporte, o `Revit` possui três referências de coordenadas:

| <img src="https://lh7-us.googleusercontent.com/ERsT6Fp0a4Onmi_KTru013-iS_G-47YydrWARUaGWaUUcSIzJMb3qeJ9DkKKPOwubpmnPtkB_Pup2EkWBmicDUKsV9HqIohewbhNEMhvh8-JDWgdg6JQ-Igoj5Rz9n3GIjNXWSwx0RpEMtvDkPUHag" alt="" data-size="original"> | ![](https://lh7-us.googleusercontent.com/MEjWXD5vLTRQkbbzR\_HGbuacI7qNRQSD55zP2DCVvdTJ0FYhXhh2UXH9ZcGbT1p1SBURelKEXj\_NvkzpvaUULoDNXL6FG39RGIgmZosTR7A\_2Mws3CTQ8nwUG0PwNasFB8UQoxhoO7xt9Q8eNjn6rg) | ![](https://lh7-us.googleusercontent.com/JNTtb1-YE6x\_1HKFhRACWxFiRSMG-D89-HICcnfmgrubfofA3UuaZKYYZ41-lf4s7uG2cxlb6\_gu7UHGs-0gKrUTCq24LyBObx3ZzqJh7dFU3al64x-0egBEooPbIDF-AOhwNYQoB-DedeiNDtnd2Q) |
| ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Origem interna                                                                                                                                                                                                                      | Ponto base de projeto                                                                                                                                                                               | Ponto Topográfico                                                                                                                                                                                  |

Para que não haja erros e nem “retrabalho”, recomenda-se que as configurações para vinculação comecem no início do projeto e da modelagem. Abaixo algumas instruções para facilitar esse processo:

### 2. PARA INÍCIO DE PROJETOS E DE MODELAGEM:

1. Ao iniciar o projeto - sempre utilizando o `template` mais atualizado - verificar se as três referências estão visíveis. Elas devem aparecer nas plantas baixas e nas elevações. Inicialmente, o ponto base do projeto e o ponto de pesquisa estão localizados na mesma posição, o ideal é que eles estejam alinhados.

<figure><img src="https://lh7-us.googleusercontent.com/wAPg66HNiZLV_5gQ8qzIgcTXUpVk26ZnTc041oRx6muILh_L46PocvyCB3PUyK_P95x8Ew9IOzetmxNYConmh4cUBiNcZ-hUsspzDoBMkDF88rKmNgVIujTYAGYC0oGHlf0a6mRdBd6gbFOS5jUL_w" alt="" width="188"><figcaption><p>Pontos de referência do Revit</p></figcaption></figure>

2. Caso não estejam visíveis, dar o comando “VG” para abrir a caixa de Visibilidade/Sobreposição de gráficos. Vá em “Categorias de modelo” e em “Visibilidade” procure por “Terreno” e selecione “Origem interna”, “Ponto base do projeto” e “Ponto de levantamento topográfico”. Lembrando que as referências precisam estar visíveis nas plantas baixas (em especial na Implantação e no Térreo que geralmente é o nível “0,0,0”) e nas elevações.

<figure><img src="https://lh7-us.googleusercontent.com/vgzXU7jDkjdyyWUmyrPlt7wHjduP1t7lqu5_ih_Non3GvSRDlJCdM9n2eVLXAlMBG81lxvysMmWliryMJ8HVOVWrdCYVPuW7ukUml_s76SiPE1Bye7rtlzbLRlWpQszasoICqG2-ALsoEjy4dl6UCw" alt=""><figcaption><p>Tela dos critérios de Visibilidade/Sobreposição do Revit (Tecla de Atalho VG)</p></figcaption></figure>

3. Iniciar o modelo a partir dos três sistemas de coordenadas. As coordenadas devem ficar sempre na primeira extremidade do edifício (nas faces) e sempre nessa posição (canto inferior esquerdo).

<figure><img src="https://lh7-us.googleusercontent.com/3VQIlRB3VHXM52zXCOYRg-Bw8EtMbcMllcM4SqdLDwXLGfkNxXz-9m9F_BLOUbcfwAU8PFQoSv5CTYkBCcxrcr7NQafKC3gHrM94AAkxYS32xuZq1l7vmxyAKlgkpR6eha5CKjwHA0NyYf-iWclSfg" alt=""><figcaption><p>Exemplo das referências em Planta.</p></figcaption></figure>

<figure><img src="https://lh7-us.googleusercontent.com/_9hU1Z8XqTJw-lKlKnbXdrj7xTbZYYLyX-vOpKe_rRl6pti30mdH6FNF2VxtQ7nbQ9bJej_6XV-ZYE4rLPG15Gkg_ooDnfSenFccK_wt7mUl8OqwI5_iiWCERiuxysLzQvQjzwikzZnd2ttp47uPbA" alt=""><figcaption><p>Ponto de referência a ser adotado em todas as plantas</p></figcaption></figure>

### 3. NORTE DE PROJETO E NORTE VERDADEIRO

1. Após visualizar as referências de coordenadas, deve-se orientar o modelo ao “Norte de Projeto” e ao “Norte Verdadeiro”. Na “PLANTA DE IMPLANTAÇÃO” deve-se lançar a anotação do NORTE MAGNÉTICO conforme a orientação da planta nas pranchas de projeto.

<figure><img src="https://lh7-us.googleusercontent.com/7GuWTyS1Dymr5Hosyzu16_M1ckXP79ac_qTQSyHRw4wuQin-jFqHGrCgsZlnxPq_Yg9ZlU85Ep3-ehXqoIMH0vdGQcrg0Xek4h5Z_TdWMv79600142CfQGu9CEW6HXVFvSGZn-lqKshHO9AkQLXTtQ" alt=""><figcaption></figcaption></figure>

2. Na aba do “Navegador de Projetos” em “Plantas de Piso”, deve-se duplicar com detalhamento a “PLANTA DE IMPLANTAÇÃO”. Renomear a cópia para “NORTE VERDADEIRO - PLANTA DE IMPLANTAÇÃO”.

<figure><img src="https://lh7-us.googleusercontent.com/bMVFroVbCQ4K_66iCS1BcoJgq4uG2cA3gNzbDzltmZ5iEeI5_faoAk2p6HdW33V9pRt1qbU9RIzIV-6_xqZRfVE5SeaIVrKBo-sx239Eh0goRRkP89HmY9q6tGdovEHjS7GII8UWanozx-RY5FmpVg" alt=""><figcaption></figcaption></figure>

3. Entrar na vista “NORTE VERDADEIRO - PLANTA DE IMPLANTAÇÃO” e visualizar o caminho do sol.

<figure><img src="https://lh7-us.googleusercontent.com/_c6zGpgJmGE3E8OohZMoD_Z240hXCpWKWezJ8MoY0z4wvox2sMMIEN14UJuq3mKp0wZTBXYhgViFJ8bqe0JPQnpcaeM0Odf05J1pN_E_mEpv_HBuSJxKFlCDRVrBo87k9nqOeYLw1FzbCT7EZ8OSXQ" alt=""><figcaption></figcaption></figure>

4. De forma automática, o Revit estará com o Norte para cima. O desenho exemplifica que o norte deste projeto é para baixo, conforme imagem a seguir.

<figure><img src="https://lh7-us.googleusercontent.com/R3kRZ8bHnO8TsXXhMoehF6EvqO-XgEVWMVicL44GFfKXazGWdxveTLnczVzdmsrTCxVsGfryYMSVdZD-ytq-AVO81AxtifyB_aB7-2spoSE2CwtOu49UsH1KwKrHDO65P84FmvmVhvikqpd-VbmEjQ" alt=""><figcaption></figcaption></figure>

5. Agora vamos corrigir o “Norte Verdadeiro”. Na aba “Propriedades” vá em “Orientação” e selecione “Norte Verdadeiro”.

<figure><img src="https://lh7-us.googleusercontent.com/90uTTOwGyyh3IxPcD0AIcc7l3siaHtOSVxR8BZiOtqTwOVRA7LOWLXVmRmxOh91XTJprR3Z6zlzXnsVgUmbbBmHYjN_4lCE8JFOX4WEKrY2piqTzAar-yXrZ3jKvjnxNUpUvRETKraYpun5Vhb_9SA" alt=""><figcaption></figcaption></figure>

\


6. Vá em “Gerenciar” e clique em “Rotacionar o norte verdadeiro”. Irá surgir a opção de rotacionar todo o modelo, rotacione para o ângulo certo do norte, fazendo com que a fachada norte fique paralelo ao norte do Revit.

<figure><img src="https://lh7-us.googleusercontent.com/YZSpcSXiWrRWCF3FuxJULY-Lpy3g1KDIlcsvFQA3gr4I0aZEXSTW_QObpI3AlodX_ZVSwLkqkf03jFUhI0_SxEsdzImQt-sVDzE_Gttzlx5n9cA3GR_exR_vEoeg64dzFsBb-o_N-cwR_o7JiZG6Pg" alt=""><figcaption></figcaption></figure>

<figure><img src="https://lh7-us.googleusercontent.com/6MJGleg0tYnW9BbYwzCzaOTkvUkOZfl6xlw3n7cRnTs2ZzviYNRMIcC4kr1SRB7fFLDOGPzne23TI9eLHPT7dejrF3V6zUsTed15p4g9-vS2MJfVxLFYDj3q9oZZ4Ar3jXZ9nIphIsMmG7PvEXageA" alt=""><figcaption></figcaption></figure>

7. De acordo com o desenho exemplificado, na vista “PLANTA BAIXA – TÉRREO” em que a Orientação está em “Norte de Projeto”, o norte está para baixo conforme o layout a ser utilizado nas pranchas. Dessa forma é mais prático a vinculação e também a análise de sol e sombreamento do projeto.

<figure><img src="https://lh7-us.googleusercontent.com/KIClmE7iL1E9rX_0gtLd68SOBZXV5uyQgPE1w6ozQjawH_mPK6E19WJg3KEoixCTpmk3SayfI0ao2lz_NCElYEIXZgpyqRACs1EfSRJ8_8T9c1V0dckhKpWTgQ5kbrhcDWTz7RgIBUBJ" alt=""><figcaption></figcaption></figure>

8. Após corrigido a orientação do “Norte Verdadeiro”, vá em “Gerenciar” e “Localização”. Essa janela possibilita a locação exata do modelo no loteamento com as referidas coordenadas - nesse ponto do terreno o caminho do sol e o sombreamento estarão corrigidos conforme a região.

<figure><img src="https://lh7-us.googleusercontent.com/ZPxOHgs-NCDYDqbLxvUGKrnDzYJs5qf0P24cACvxk0a9-xfeHKurR7wB5T1v17bB0w5su3Zw_Bty1MhimZ6W27JClHhFlsrcQGpRylnOffzlcT814mxVluR78lu59GJlJn0qGW8Mma9r" alt=""><figcaption></figcaption></figure>

### 4. INICIAR UM PROJETO EM UM EDIFÍCIO JÁ MODELADO - REFORMAS

Caso o projeto tenha sido modelado fora das referências de coordenadas, será necessário movimentar o “Ponto base de projeto” (PB) para a extremidade conforme citado no item 1.3. É importante salientar que o “Ponto de Origem Interna” não se movimenta, então nesse caso só será possível mover o PB. Deve-se:

1. Ativar a visualização das três referências de coordenadas;
2. Caso o projeto já esteja modelado e fora do ponto da origem interna, mover o ponto base de projeto;
3. Após locar o ponto base de projeto na coordenada certa, corrigir o norte de projeto e o norte verdadeiro;
4. Nesse caso, as vinculações de projetos e as extrações de IFC devem ser feitas com “Base de coordenadas: Ponto Base de Projeto”.
5. INSERINDO VÍNCULO DE REVIT
6.
   1. Para vincular arquivos RVT ou de IFC em um arquivo RVT e gerir a compatibilização de forma integrada, deve-se verificar se em todos eles os sistemas de coordenadas Revit estão coesos (Ponto base de projeto e Origem interna).
   2. Vá em “Inserir” e depois “Vínculo do Revit”, selecione o arquivo e em “Posicionamento” clique em “Automático - Da origem interna para a origem interna” caso o edifício esteja com as referências em Ponto base de projeto e Origem interna, caso a origem interna esteja em outro ponto e o modelo esteja somente com o Ponto base de projeto em sua extremidade, clique em “Automático - Do ponto base do projeto para o ponto base do projeto.

<figure><img src="https://lh7-us.googleusercontent.com/SLkBNxLlxUt4OYNYYNit_QGNXKVQOfMj-Cq5xt02eqKI7Ezti6MoGC5rXn69AFL7OSSLSsjCxJ8LxXHaPXVPRpHWaiFK1MzFQhx39J9kaS2BaZIXkWMKNgYGoRrL92DwiyN73IrV2ooa" alt=""><figcaption></figcaption></figure>

<figure><img src="https://lh7-us.googleusercontent.com/hfqceRAWDrKbU_4MqdKV0vRvwBp9lo_RNPQSjwzLXVyMtupU_bA0-ZHks4imnBFRCPSeOjFY4J9na65Bd6BAwZSny1jYkgVPf7Koybi-H8mZuQ0YRE_BeKHf0TgunQjEOfhzG3pFNMf1" alt=""><figcaption></figcaption></figure>

### 5. EXPORTANDO IFC

1. Vá em “Arquivo”, “Exportar” e clique em “IFC”. Selecione o projeto o qual será exportado e clique em “Modificar a configuração”.

<figure><img src="https://lh7-us.googleusercontent.com/tU-pAJY4tS30FafIDK9CGepL_zyx3YwxgUHIZtczxA26G4k8W03CIlA5d4xWVTJC1Vy2cWNWSrf3qw32tT1p87r0A3cnUG47NCV24STb-pLkxZbK-0JOhhj3RgpkxCiNvNwkdS15WZ9_" alt=""><figcaption></figcaption></figure>

2. Na janela clique em “Geral”. No campo “Fase para exportar” selecione “FINAL” ou a fase (Existente, demolir e etc.) que estiver usando. Depois, em “Base de coordenadas”, selecione “Origem Interna”. Caso a origem interna esteja em outro ponto e o modelo esteja somente com o Ponto base de projeto em sua extremidade, clique em “Ponto base do projeto”.

<figure><img src="https://lh7-us.googleusercontent.com/4PQd0uuwXoungDCr3zd1eO6JxX7oHLrEBU7zidEoGpyxUWRpBICjo_hOu_T4Uz_PhRFp95eTaUbV3npHdZv-BpxRuzwMPPFqDJIaNgVrG38dAndthBZryEPHElCtr9yM8keLLtETZiMq" alt=""><figcaption><p>Tela de exportação do Revit para modelos IFC </p></figcaption></figure>

\
