<!DOCTYPE html>
<html>
<head>
    <title>Pontos Turísticos Salvador - Lua de Mel</title>
</head>
<body>
    <h1>Pontos Turísticos em Salvador - Lua de Mel</h1>

    <ul id="lista-pontos-turisticos">
        <li>Ilha de Tinharé e Boipeba de lancha - R$ 89</li>
        <li>Bahia 500 anos - R$ 75</li>
        <li>Sol, mar e magia - Olha dos frades e Itaparica - R$ 140</li>
        <li>Sítio Tour na primeira capital do Brasil - R$ 127</li>
        <li>Escapa praiana praia do forte - R$ 122</li>
        <li>Dia inteiro no Morro de São Paulo - R$ 215</li>
        <li>Maravilhosas litorâneas - R$ 115</li>
        <li>City tour panorâmico - R$ 80</li>
        <li>Brilho do litoral - Praia do Forte - R$ 130</li>
        <li>Paraíso Baiano - R$ 150</li>
        <li>City tour por Instagramável - R$ 92</li>
        <li>Translado ida e volta para Morro de São Paulo - R$ 275</li>
        <li>Praia dos sonhos - Ilha dos Frades - R$ 166</li>
        <li>Passeio a Morro de São Paulo - R$ 312</li>
        <li>Passeio a Praia do Forte - R$ 170</li>
        <li>Tour rota da liberdade vida no quilombo - R$ 235</li>
        <li>Tour privativo Salvador essencial 6hrs - R$ 207</li>
        <li>Ilhas da Bahia - R$ 240</li>
        <li>City tour privativo herança africana - R$ 262</li>
        <li>Tour as Dunas mangue seco com Buggy - R$ 352</li>
        <li>Passeio de escuna na Ilha dos Frades - R$ 181</li>
        <li>Encantos do mar - Praias de Salvador - R$ 105</li>
        <li>Tour histórico e panorâmico - R$ 164</li>
        <li>Ritmo do Pelô - R$ 142</li>
        <li>Pacote especial Elevador Lacerda - R$ 183</li>
        <li>Bahia à noite - Show folclórico - R$ 202</li>
        <li>Tour 3 praias: Itacimirim, Sto Antônio e Imbassaí - R$ 174</li>
        <li>Tour histórico panorâmico com almoço - R$ 243</li>
        <li>Tour sabores e amores - R$ 175</li>
        <li>Casa do rio vermelho - História do Jorge Amado - R$ 93</li>
        <li>Tour mistério do candomblé da Bahia - R$ 213</li>
        <li>Tour privativo nos museus de Salvador - R$ 116</li>
    </ul>

    <button onclick="adicionarItem()">Adicionar Item</button>

    <script>
        function adicionarItem() {
            var lista = document.getElementById("lista-pontos-turisticos");
            var novoItem = document.createElement("li");
            novoItem.innerHTML = "Novo Ponto Turístico - R$ 0"; // Personalize o novo item conforme necessário
            lista.appendChild(novoItem);
        }
    </script>
</body>
</html>
