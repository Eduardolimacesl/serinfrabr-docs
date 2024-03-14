---
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

# 🌎 Revit: Ponto de origem

### 1. CRIAÇÃO DO MODELO

Os projetistas devem atentar para não fazerem alterações nos templates. Para iniciar um modelo, clicar em "Novo...", carregar o template ("Arquivo Modelo") e "Criar Novo:Projeto".

<figure><img src="https://lh7-us.googleusercontent.com/wa7Uxmz-ke9-Z2hNKWODIgcnV6dY4nBZPPK2fzG-3HKdiPYJegax-5I1QcPi7Bj9pv2D_pxMzHw2LCiIeSbqbgPLSOFkfTVU7PoJKfOsXCLCV1T7D-kAJ_c2RolJAu-htj99QodSUBFMRtsXZ4jdZQ" alt=""><figcaption></figcaption></figure>

Após o início do projeto, é necessário selecionar a correta disciplina padrão de vista. Clicar em "Opções" e selecionar a disciplina correspondente.&#x20;

\
![](https://lh7-us.googleusercontent.com/MdoOLUa2guQWpilwSAc0qwkVatw2o-VqL1x\_H4GRKpRlihjRV7y1UfgCHj0dltkgXAb6w\_QsCXKI18HnRxE4sDldkRQfP5ssbmO0Mf4r5NFdBwyzR3lJqCR2o5fiixd1bTcDVWo7oi2czp5NynGD7Q)![](https://lh7-us.googleusercontent.com/U2YE6nui3dhU\_Td\_XdS3Wi71yqYPzZufNM8L7tepi6nyG2ZJn\_-TW\_KmSMFPQOI5gc\_ij2dUwGz\_ShJKRWKsXVDdCGmTwo7UDgQqJkFcwiPIuYu1tSv5T-QV3H7JAinruo2qLgI2T2EwBJEJVunu2g)

### 2. UNIDADES DE PROJETO

As unidades de projeto deverão ser configuradas como segue. Para acessá-las, usar o atalho "un".

<figure><img src="https://lh7-us.googleusercontent.com/rWJ7zJwXID5oZjO3mPytP9qCKUso_juzYtX_5x8LDHn_dp4IBHsbC--J-4RrKQJc-pzxZdAbDYdAhs8uBX97GtA8HaG-ST3KRkiQWJFAif9-P6-GtVg1FSV3Lq5o9XcuQR5ckhZluK_7NcQre1U4cA" alt=""><figcaption></figcaption></figure>

### 3. PONTO DE PESQUISA E PONTO BASE

Primeiramente, deve-se certificar que as categorias estão visíveis na vista desejada. Caso contrário, habilite sua "visibilidade/sobreposição", usar o atalho "vg", na aba "terreno". Buscar pelo "ponto base" e "ponto de pesquisa" conforme a seguir.

<figure><img src="https://lh7-us.googleusercontent.com/NU84jkrJxdzYSDWPkLbTab9inMiJttyHBnWhXsGDYdqio8iWFZtyCRwcAtPp_KBls8Xn6I59df6ZPD-LAqNhOalEBwZIYjgFEqKpK0x5LmVjdDg2foGdToS1HP3x3y0ZDRCz4myPfOMe6ericjslpw" alt=""><figcaption></figcaption></figure>

O ponto de pesquisa do projeto (ponto de levantamento geográfico) é definido no projeto com as seguintes coordenadas, em metros, caso a disciplina utilizar outra unidade deverá configurar a unidade “un” do projeto para metros e assim continuar o procedimento abaixo:

| N/S      | 7399635.5049 |
| -------- | ------------ |
| L/O      | 333023.5262  |
| Elevação | 723.3350     |

O ponto base do projeto é definido no encontro do eixo 1 com o eixo A, sendo a coordenada em metros, que  segue:

| N/S                          | 7399661.7324 |
| ---------------------------- | ------------ |
| L/O                          | 333037.6726  |
| Elevação                     | 723.000      |
| Ângulo para norte verdadeiro | 5°           |

Para inserir as informações das coordenadas nas propriedades do ponto de pesquisa e ponto base, deve-se seguir o procedimento a seguir:

{% hint style="danger" %}
Observação: O ponto base e os eixos 1 e A estão sobre as coordenada oculta 0,0,0 do Revit. Esta coordenada é utilizada apenas para as interações entre softwares na leitura dos arquivos IFC. O procedimento abaixo fará com que o projeto seja posicionado na coordenada geográfica sem que as coordenadas ocultas do Revit sejam modificadas. O comando mover para os eixos e ponto base não deve ser utilizados em hipótese alguma.
{% endhint %}

1. Dentro de uma planta de piso qualquer, atribuir um modelo de vista como “nenhum” no caminho: “Propriedades”→”Dados de identidade” →”Modelo de vista”&#x20;

<figure><img src="https://lh7-us.googleusercontent.com/dHvauUIJCiF69XHjTlR5YV9u0Rfsyt5N_LiwA5j3yjC2nGhconHEuo2IsEHdeJo69kZy0Fq5XK0wGtZatvqMIUECSFsXiIUtivye-zcV2FWdIBUATTf6BwIFsqshzH4XuWKVm49g9hyT2ki4OLD4Zw" alt=""><figcaption></figcaption></figure>

2. Selecionar lâmpada na barra de ferramentas inferior para revelar elementos ocultos.

<figure><img src="https://lh7-us.googleusercontent.com/211vjHOKtp5GT-r0dsh2ebbxbE23D9SWWoBJP2uGgsWb3Ps7UzVpIc0xFV0ZhW-F5uW20pWgHhUbrQYj45aHJcq8Xe33Nku3ZyEQCWdMqjwZGn0bX-uVZe5lbhTuNy9GnRMXBlsVKFmq0S7R_N994w" alt=""><figcaption></figcaption></figure>

3. Selecionar o ponto de pesquisa (aproximando o mouse e usando TAB ou selecionando a região e usando a ferramenta filtrar) e "desclipar" o elemento para habilitar sua edição.

<figure><img src="https://lh7-us.googleusercontent.com/wsHtvKHBVHzW8fzEOQ64ZtPc3MurRfyiTz9HNwQ1jg-MMjJ3Svfscv_fYwM2lcLNFzCzA56dcAwjGwOKPTj1zy6Esi2L9RFJ7YpyFZB6mO4JX7mDNJPc2dwcOA4DMMnvXoh4pqUBt7PsJgodIKTlrQ" alt=""><figcaption></figcaption></figure>

4. Digitar as coordenadas (o ponto de pesquisa não estará mais visível).

<figure><img src="https://lh7-us.googleusercontent.com/_MPUAGRxXvjDdXFDzoyOijhiZnX5YS6vuQx4n3QN-MHpKnf0W1fLyEPh_DFMWqD3bKKtYOC3tehO27ZLDcBEAExEr2lxq3k8F2vLRtwD4KtPYNqmAr5HUcElyeHZpt5D8QGRfR_AQ9Ok7H-MNx8hpw" alt=""><figcaption></figcaption></figure>

5. Selecionar o ponto base, desafixar (ele deve permanecer “clipado”) e digitar as coordenadas.

<figure><img src="https://lh7-us.googleusercontent.com/99JGInCa23JAE8hv-XE51Q26OXl-06cQ3hYk-ywdAAmwLQUkRTbZ_Lg_pLsg4xyZY5Mx8K8wVGWaYK3iwrAxv9Fma5e1MrJvfmok9gq5Bl1j7RpZ570F50nJKrUeeC-c8PIPd3-zB6_VVZ8JIPKI8g" alt=""><figcaption></figcaption></figure>

\


<figure><img src="https://lh7-us.googleusercontent.com/zjxdaCdSQNKtr2364yQ-teMNmLPqBMUJr-DqPDuUDI3GYVSfk3atGmSkOE6-7JdsjsIRqfwxGNk-caE2aOEcs_oJfRkqjCNBuvk3gv8x4GT-FbM6Dkoxt3Lw6Vym6d5d6R7zd_LWqx1hbShq6AAoig" alt=""><figcaption></figcaption></figure>

6. Todo o projeto se deslocará para a coordenada desejada. Para visualizar os pontos novamente, usar o comando “Zoom Extends” (atalho ZE ou clicando no menu lateral direito, conforme indicado a seguir). Vale destacar que o comando mover não deve ser utilizado para reposicionar o ponto base ou os eixos, para não retirá-los do 0,0,0 do Revit.

<figure><img src="https://lh7-us.googleusercontent.com/Ab1LRX1TW6clNA_SqHgSVATyFihDBm_yhpE4QW6SbaLy1tQvCx-Cm0qTiIV5Z1DntFFi0luz1NS9IvPGLj7lves36gD1HiDej3KwAyyiVSd82uOiosxsxzJG919DjeyigcwS4WkjA0OFHq8dJ0qxNA" alt=""><figcaption></figcaption></figure>

<figure><img src="https://lh7-us.googleusercontent.com/tU2A2K8ZB8DtpO11gUt7bcBeVPFzrCy3_Gmzm8GqgHYYhUwfCoY4IRNxoaizNIKxdSAhdIQzSIg2hBMAe4dfgx82vdFA9SlJp2kVRU7yrjwbNphJ41QmIKFyOJQxUZn8nrEOZfoK5P_Bm_hFgl4ygg" alt=""><figcaption></figcaption></figure>

7. Fixar e clipar o ponto base.&#x20;

<figure><img src="https://lh7-us.googleusercontent.com/6Jmdp3mFcErkna6_P118BDXBntJF8y7nQU7k7QrpbwA2-nx2flT67MgQzN2UnRrSEvtXNP53fuv8cB9IlV9QxLpRgrXApAjuT33z90hdLJZnL2NBUVX2c1K3d6bNuO7OBlZ0uU1rM_skyOs4RfsrPQ" alt=""><figcaption></figcaption></figure>

8. “Clipar” ponto de pesquisa para as propriedades do ponto não serem mais alteradas.

<figure><img src="https://lh7-us.googleusercontent.com/mDRRyLC72zaB1oECpgYd_otfClA1ZwqFsaCiyp7gKmjkE1QTRPC5ydeSXuH3SBe_NZCArdY_GJehA5GVFywbJm0nnUrjP2LpRNU_UZudmtoykbPHLm9mcqAN8ByXXwAI-XmCLsS4vhPQklV9CJT-Lg" alt=""><figcaption></figcaption></figure>

<figure><img src="https://lh7-us.googleusercontent.com/RUnEBuTVla5RMg3xNWgL8a4vMDWHQ7mIQk83s4GpGpZXU8ej9ci54_WkFDcT8vOwqT8NvUJjlPUQbReem40b6r6wJDPPwSQTvDZY4HII8-bVlmgmkDTPr8-XWzUFi81sPYxWKFoQ2mY_ueFw_sPGqw" alt=""><figcaption></figcaption></figure>

9. Dessa forma, para a disciplina de arquitetura o modelo está pronto para o início do projeto, para as outras disciplinas, deve ser inserido o vínculo de Revit, com o posicionamento “Auto –  origem para origem”.

<figure><img src="https://lh7-us.googleusercontent.com/OPmQ5cCHGCj4hqBi4t7mlgu66C4CSG2ej0hu0kyAI_Kvb040kN6wiw7gFZXLYcXZ3aTLGzRH68j9Xrry5ZsgPX1Ry6qrccEHC0faAQzi6d6FtCMLD5h-FAKG68xwhUJiYprzXah_9DhdkZslS7AG3w" alt=""><figcaption></figcaption></figure>

\
\
