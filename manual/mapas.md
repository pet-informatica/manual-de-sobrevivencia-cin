# Mapas

<style>
    .tabset > input[type="radio"] {
    position: absolute;
    left: -200vw;
    }

    .tabset .tab-panel {
    display: none;
    }

    .tabset > input:first-child:checked ~ .tab-panels > .tab-panel:first-child,
    .tabset > input:nth-child(3):checked ~ .tab-panels > .tab-panel:nth-child(2),
    .tabset > input:nth-child(5):checked ~ .tab-panels > .tab-panel:nth-child(3),
    .tabset > input:nth-child(7):checked ~ .tab-panels > .tab-panel:nth-child(4),
    .tabset > input:nth-child(9):checked ~ .tab-panels > .tab-panel:nth-child(5),
    .tabset > input:nth-child(11):checked ~ .tab-panels > .tab-panel:nth-child(6) {
    display: block;
    }

    .tabset > label {
    position: relative;
    display: inline-block;
    padding: 15px 15px 25px;
    border: 1px solid transparent;
    border-bottom: 0;
    cursor: pointer;
    font-weight: 600;
    }

    .tabset > label::after {
    content: "";
    position: absolute;
    left: 15px;
    bottom: 10px;
    width: 22px;
    height: 4px;
    background: #fb6b02;
    }

    .tabset > label:hover,
    .tabset > input:focus + label {
    color: #fb6b02;
    }

    .tabset > label:hover::after,
    .tabset > input:focus + label::after,
    .tabset > input:checked + label::after {
    background: #06c;
    }

    .tabset > input:checked + label {
    border-color: #ccc;
    border-bottom: 1px solid #fff;
    margin-bottom: -1px;
    }

    .tab-panel {
    padding: 30px 0;
    border-top: 1px solid #ccc;
    }

    .map-svg {
    width: 98%;
    }

    #index-search {
    outline: none;
    border-bottom: 1px solid #ccc;
    border-top: none;
    border-left: none;
    border-right: none;
    background: transparent;
    height: 50px;
    padding: 20px 5px 0 0;
    font-size: 18px;
    color: #666565;
    margin-bottom: 12px;
    font-family: "Fira Sans", sans-serif;
    }
</style>

## Blocos A, B e C

Os blocos A, B e C compõem o prédio vermelho do CIn.

<div class="tabset">

<input type="radio" name="tabset-abc" id="sel-abc-terreo" aria-controls="abc-terreo" checked>
<label for="sel-abc-terreo">Térreo</label>

<input type="radio" name="tabset-abc" id="sel-abc-1-andar" aria-controls="abc-1-andar">
<label for="sel-abc-1-andar">1º andar</label>

<input type="radio" name="tabset-abc" id="sel-abc-2-andar" aria-controls="abc-2-andar">
<label for="sel-abc-2-andar">2º andar</label>

<div class="tab-panels">
<section id="abc-terreo" class="tab-panel">
<img class="map-svg" src="assets/svg/maps/abc_t.svg"></img>
</section>
<section id="abc-1-andar" class="tab-panel">
<img class="map-svg" src="assets/svg/maps/abc_1.svg"></img>
</section>
<section id="abc-2-andar" class="tab-panel">
<img class="map-svg" src="assets/svg/maps/abc_2.svg"></img>
</section>
</div>

</div>

## Bloco D

O bloco D compreende as salas que se localizam no prédio do CCEN.

## Bloco E

O bloco E compõe o prédio branco do CIn.

<div class="tabset">

<input type="radio" name="tabset-e" id="sel-e-terreo" aria-controls="e-terreo" checked>
<label for="sel-e-terreo">Térreo</label>

<input type="radio" name="tabset-e" id="sel-e-mezanino" aria-controls="e-mezanino">
<label for="sel-e-mezanino">Mezanino</label>

<input type="radio" name="tabset-e" id="sel-e-1-andar" aria-controls="e-1-andar">
<label for="sel-e-1-andar">1º andar</label>

<input type="radio" name="tabset-e" id="sel-e-2-andar" aria-controls="e-2-andar">
<label for="sel-e-2-andar">2º andar</label>

<input type="radio" name="tabset-e" id="sel-e-3-andar" aria-controls="e-2-andar">
<label for="sel-e-3-andar">3º andar</label>

<input type="radio" name="tabset-e" id="sel-e-4-andar" aria-controls="e-2-andar">
<label for="sel-e-4-andar">4º andar</label>

<div class="tab-panels">
<section id="e-terreo" class="tab-panel">
<img class="map-svg" src="assets/svg/maps/e_t.svg"></img>
</section>

<section id="e-mezanino" class="tab-panel">
<img class="map-svg" src="assets/svg/maps/e_m.svg"></img>
</section>
<section id="e-1-andar" class="tab-panel">
<img class="map-svg" src="assets/svg/maps/e_1.svg"></img>
</section>
<section id="e-2-andar" class="tab-panel">
<img class="map-svg" src="assets/svg/maps/e_2.svg"></img>
</section>
<section id="e-3-andar" class="tab-panel">
<img class="map-svg" src="assets/svg/maps/e_3.svg"></img>
</section>
<section id="e-4-andar" class="tab-panel">
<img class="map-svg" src="assets/svg/maps/e_4.svg"></img>
</section>
</div>

</div>

## Índice

<input type="search" onkeyup="filterTable()" id="index-search" placeholder="Pesquisar...">
<table id="index-table">
<tbody>
<tr>
    <th>Sala</th>
    <th>Descrição</th>
    <th>Bloco e andar</th>
</tr>
<tr>
    <td><b>A001</b></td>
    <td>Silvio Melo</td>
    <td>Bloco A, Térreo</td>
</tr>
<tr>
    <td><b>A002</b></td>
    <td>Simone Santos</td>
    <td>Bloco A, Térreo</td>
</tr>
<tr>
    <td><b>A003</b></td>
    <td>Tsang Ingren</td>
    <td>Bloco A, Térreo</td>
</tr>
<tr>
    <td><b>A004</b></td>
    <td>Robson Fidalgo</td>
    <td>Bloco A, Térreo</td>
</tr>
<tr>
    <td><b>A005</b></td>
    <td>Fred Freitas</td>
    <td>Bloco A, Térreo</td>
</tr>
<tr>
    <td><b>A007</b></td>
    <td>Henrique Rebelo</td>
    <td>Bloco A, Térreo</td>
</tr>
<tr>
    <td><b>A009</b></td>
    <td>Sóstenes</td>
    <td>Bloco A, Térreo</td>
</tr>
<tr>
    <td><b>A010</b></td>
    <td>Ricardo Massa</td>
    <td>Bloco A, Térreo</td>
</tr>
<tr>
    <td><b>A011</b></td>
    <td>Cristiano Araújo</td>
    <td>Bloco A, Térreo</td>
</tr>
<tr>
    <td><b>A012</b></td>
    <td>Carina Frota</td>
    <td>Bloco A, Térreo</td>
</tr>
<tr>
    <td><b>A013</b></td>
    <td>Sérgio Soares</td>
    <td>Bloco A, Térreo</td>
</tr>
<tr>
    <td><b>A014</b></td>
    <td>Sala de Aula</td>
    <td>Bloco A, Térreo</td>
</tr>
<tr>
    <td><b>A015</b></td>
    <td>Fernando Castor</td>
    <td>Bloco A, Térreo</td>
</tr>
<tr>
    <td><b>B001</b></td>
    <td>Renato Vimiero</td>
    <td>Bloco B, Térreo</td>
</tr>
<tr>
    <td><b>B003</b></td>
    <td>CITi</td>
    <td>Bloco B, Térreo</td>
</tr>
<tr>
    <td><b>B004</b></td>
    <td>Laboratório de Pesquisa</td>
    <td>Bloco B, Térreo</td>
</tr>
<tr>
    <td><b>B005</b></td>
    <td>Laboratório de Usabilidade</td>
    <td>Bloco B, Térreo</td>
</tr>
<tr>
    <td><b>B006</b></td>
    <td>Laboratório de Usabilidade</td>
    <td>Bloco B, Térreo</td>
</tr>
<tr>
    <td><b>B007</b></td>
    <td>Gerência de Infraestrutura</td>
    <td>Bloco B, Térreo</td>
</tr>
<tr>
    <td><b>B008</b></td>
    <td>Voxar Labs</td>
    <td>Bloco B, Térreo</td>
</tr>
<tr>
    <td><b>B009</b></td>
    <td>PET</td>
    <td>Bloco B, Térreo</td>
</tr>
<tr>
    <td><b>B011</b></td>
    <td>Suporte e Adm. de Sistema</td>
    <td>Bloco B, Térreo</td>
</tr>
<tr>
    <td><b>B013</b></td>
    <td>Laboratório de Pesquisa</td>
    <td>Bloco B, Térreo</td>
</tr>
<tr>
    <td><b>B015</b></td>
    <td>Oficina</td>
    <td>Bloco B, Térreo</td>
</tr>
<tr>
    <td><b>B017</b></td>
    <td>Oficina</td>
    <td>Bloco B, Térreo</td>
</tr>
<tr>
    <td><b>B018</b></td>
    <td>Grad 5</td>
    <td>Bloco B, Térreo</td>
</tr>
<tr>
    <td><b>B019</b></td>
    <td>Diretório Acadêmico</td>
    <td>Bloco B, Térreo</td>
</tr>
<tr>
    <td><b>B020</b></td>
    <td>Sala de Aula</td>
    <td>Bloco B, Térreo</td>
</tr>
<tr>
    <td><b>B021</b></td>
    <td>RobôCin</td>
    <td>Bloco B, Térreo</td>
</tr>
<tr>
    <td><b>B022</b></td>
    <td>Grad 4</td>
    <td>Bloco B, Térreo</td>
</tr>
<tr>
    <td><b>B023</b></td>
    <td>Grad 2</td>
    <td>Bloco B, Térreo</td>
</tr>
<tr>
    <td><b>B024</b></td>
    <td>Grad 1</td>
    <td>Bloco B, Térreo</td>
</tr>
<tr>
    <td><b>B025</b></td>
    <td>Grad 3</td>
    <td>Bloco B, Térreo</td>
</tr>
<tr>
    <td><b>C001</b></td>
    <td>Laboratório de Hardware</td>
    <td>Bloco C, Térreo</td>
</tr>
<tr>
    <td><b>C002</b></td>
    <td>Laboratório de Pesquisa</td>
    <td>Bloco C, Térreo</td>
</tr>
<tr>
    <td><b>C003</b></td>
    <td>Laboratório de Hardware</td>
    <td>Bloco C, Térreo</td>
</tr>
<tr>
    <td><b>C004</b></td>
    <td>Renato Mariz de Moraes</td>
    <td>Bloco C, Térreo</td>
</tr>
<tr>
    <td><b>C006</b></td>
    <td>Paulo Gonçalves (pasg)</td>
    <td>Bloco C, Térreo</td>
</tr>
<tr>
    <td><b>C008</b></td>
    <td>Adriano Sarmento</td>
    <td>Bloco C, Térreo</td>
</tr>
<tr>
    <td><b>C009</b></td>
    <td>Laboratório de Pesquisa</td>
    <td>Bloco C, Térreo</td>
</tr>
<tr>
    <td><b>C010</b></td>
    <td>Paulo Adeodato</td>
    <td>Bloco C, Térreo</td>
</tr>
<tr>
    <td><b>C011</b></td>
    <td>Laboratório de Pós-graduação</td>
    <td>Bloco C, Térreo</td>
</tr>
<tr>
    <td><b>C012</b></td>
    <td>Leopoldo Motta</td>
    <td>Bloco C, Térreo</td>
</tr>
<tr>
    <td><b>C013</b></td>
    <td>Laboratório de Pós-graduação</td>
    <td>Bloco C, Térreo</td>
</tr>
<tr>
    <td><b>C014</b></td>
    <td>Eduardo Tavares</td>
    <td>Bloco C, Térreo</td>
</tr>
<tr>
    <td><b>C015</b></td>
    <td>Laboratório de Pós-graduação</td>
    <td>Bloco C, Térreo</td>
</tr>
<tr>
    <td><b>C017</b></td>
    <td>Central Telefônica</td>
    <td>Bloco C, Térreo</td>
</tr>
<tr>
    <td><b>C019</b></td>
    <td>Laboratório de Pesquisa</td>
    <td>Bloco C, Térreo</td>
</tr>
<tr>
    <td><b>A101</b></td>
    <td>Projeto OKI</td>
    <td>Bloco A, 1º andar</td>
</tr>
<tr>
    <td><b>A102</b></td>
    <td>Alex Sandro Gomes (asg)</td>
    <td>Bloco A, 1º andar</td>
</tr>
<tr>
    <td><b>A104</b></td>
    <td>Marcelo dAmorim</td>
    <td>Bloco A, 1º andar</td>
</tr>
<tr>
    <td><b>A105</b></td>
    <td>Veronica Teichrieb (vt)</td>
    <td>Bloco A, 1º andar</td>
</tr>
<tr>
    <td><b>A106</b></td>
    <td>Vinícius Garcia (vcg)</td>
    <td>Bloco A, 1º andar</td>
</tr>
<tr>
    <td><b>A107</b></td>
    <td>Sérgio Queiroz (srmq)</td>
    <td>Bloco A, 1º andar</td>
</tr>
<tr>
    <td><b>A108</b></td>
    <td>Kelvin Dias (kld)</td>
    <td>Bloco A, 1º andar</td>
</tr>
<tr>
    <td><b>A109</b></td>
    <td>Cleber Zanchettin (cz)</td>
    <td>Bloco A, 1º andar</td>
</tr>
<tr>
    <td><b>A111</b></td>
    <td>Carlos Mello (cabm)</td>
    <td>Bloco A, 1º andar</td>
</tr>
<tr>
    <td><b>A113</b></td>
    <td>Juliano Iyoda (jmi)</td>
    <td>Bloco A, 1º andar</td>
</tr>
<tr>
    <td><b>A115</b></td>
    <td>Sergio Cavalcante (svc)</td>
    <td>Bloco A, 1º andar</td>
</tr>
<tr>
    <td><b>A117</b></td>
    <td>Abel Guilhermino (agsf)</td>
    <td>Bloco A, 1º andar</td>
</tr>
<tr>
    <td><b>A119</b></td>
    <td>Bernadette Loscio (bfl)</td>
    <td>Bloco A, 1º andar</td>
</tr>
<tr>
    <td><b>A121</b></td>
    <td>Carla Taciana (ctlls)</td>
    <td>Bloco A, 1º andar</td>
</tr>
<tr>
    <td><b>A123</b></td>
    <td>Paulo Fonseca (paguso)</td>
    <td>Bloco A, 1º andar</td>
</tr>
<tr>
    <td><b>A125</b></td>
    <td>Odilon Filho</td>
    <td>Bloco A, 1º andar</td>
</tr>
<tr>
    <td><b>A127</b></td>
    <td>Laboratório de Estudos</td>
    <td>Bloco A, 1º andar</td>
</tr>
    <tr>
    <td><b>B201</b></td>
    <td>George Cavalcanti (gdcc)</td>
    <td>Bloco B, 2º andar</td>
</tr>
<tr>
    <td><b>B202</b></td>
    <td>André Santos</td>
    <td>Bloco B, 2º andar</td>
</tr>
<tr>
    <td><b>B203</b></td>
    <td>Germano Vasconcelos (gcv)</td>
    <td>Bloco B, 2º andar</td>
</tr>
<tr>
    <td><b>B204</b></td>
    <td>Anjolina Grisi</td>
    <td>Bloco B, 2º andar</td>
</tr>
<tr>
    <td><b>B205</b></td>
    <td>Paulo Borba</td>
    <td>Bloco B, 2º andar</td>
</tr>
<tr>
    <td><b>B206</b></td>
    <td>Roberto S. M. Barros</td>
    <td>Bloco B, 2º andar</td>
</tr>
<tr>
    <td><b>B207</b></td>
    <td>Patrícia Tedesco</td>
    <td>Bloco B, 2º andar</td>
</tr>
<tr>
    <td><b>B208</b></td>
    <td>Ruy Queiroz</td>
    <td>Bloco B, 2º andar</td>
</tr>
<tr>
    <td><b>B209</b></td>
    <td>Stênio Fernandes</td>
    <td>Bloco B, 2º andar</td>
</tr>
<tr>
    <td><b>B210</b></td>
    <td>Alexandre Mota</td>
    <td>Bloco B, 2º andar</td>
</tr>
<tr>
    <td><b>B211</b></td>
    <td>Francisco Tenório</td>
    <td>Bloco B, 2º andar</td>
</tr>
<tr>
    <td><b>B212</b></td>
    <td>Augusto Sampaio</td>
    <td>Bloco B, 2º andar</td>
</tr>
    <tr>
    <td><b>E101</b></td>
    <td>Sala de Reunião</td>
    <td>Bloco E, 1º andar</td>
</tr>
<tr>
    <td><b>E102</b></td>
    <td>Sala de Reunião</td>
    <td>Bloco E, 1º andar</td>
</tr>
<tr>
    <td><b>E103</b></td>
    <td>Sala de Reunião</td>
    <td>Bloco E, 1º andar</td>
</tr>
<tr>
    <td><b>E104</b></td>
    <td>Sala de Reunião</td>
    <td>Bloco E, 1º andar</td>
</tr>
<tr>
    <td><b>E112</b></td>
    <td>Sala de Aula</td>
    <td>Bloco E, 1º andar</td>
</tr>
<tr>
    <td><b>E113</b></td>
    <td>Sala de Aula</td>
    <td>Bloco E, 1º andar</td>
</tr>
<tr>
    <td><b>E121</b></td>
    <td>Sala de Aula</td>
    <td>Bloco E, 1º andar</td>
</tr>
<tr>
    <td><b>E122</b></td>
    <td>Sala de Aula</td>
    <td>Bloco E, 1º andar</td>
</tr>
<tr>
    <td><b>E123</b></td>
    <td>Sala de Aula</td>
    <td>Bloco E, 1º andar</td>
</tr>
<tr>
    <td><b>E124</b></td>
    <td>Sala de Aula</td>
    <td>Bloco E, 1º andar</td>
</tr>
<tr>
    <td><b>E201</b></td>
    <td>Sala de Reunião</td>
    <td>Bloco E, 2º andar</td>
</tr>
<tr>
    <td><b>E202</b></td>
    <td>Sala de Reunião</td>
    <td>Bloco E, 2º andar</td>
</tr>
<tr>
    <td><b>E203</b></td>
    <td>Sala de Reunião</td>
    <td>Bloco E, 2º andar</td>
</tr>
<tr>
    <td><b>E204</b></td>
    <td>Sala de Reunião</td>
    <td>Bloco E, 2º andar</td>
</tr>
<tr>
    <td><b>E211</b></td>
    <td>Auditório</td>
    <td>Bloco E, 2º andar</td>
</tr>
<tr>
    <td><b>-</b></td>
    <td>Sandpit</td>
    <td>Bloco E, 2º andar</td>
</tr>
<tr>
    <td><b>E301</b></td>
    <td>Developer Academy</td>
    <td>Bloco E, 3º andar</td>
</tr>
<tr>
    <td><b>E403</b></td>
    <td>Sala de Reunião</td>
    <td>Bloco E, 4º andar</td>
</tr>
<tr>
    <td><b>E411</b></td>
    <td>Laboratório de Pesquisa</td>
    <td>Bloco E, 4º andar</td>
</tr>
<tr>
    <td><b>E412</b></td>
    <td>PITCH</td>
    <td>Bloco E, 4º andar</td>
</tr>
<tr>
    <td><b>E422</b></td>
    <td>Laboratório de Pesquisa</td>
    <td>Bloco E, 4º andar</td>
</tr>
<tr>
    <td><b>E423</b></td>
    <td>Sala de Aula</td>
    <td>Bloco E, 4º andar</td>
</tr>
</tbody>
</table>