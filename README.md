## 👨‍💻 Autor

<div align="center">
  <img src="https://avatars.githubusercontent.com/ninomiquelino" width="100" height="100" style="border-radius: 50%">
  <br>
  <strong>Onivaldo Miquelino</strong>
  <br>
  <a href="https://github.com/ninomiquelino">@ninomiquelino</a>
</div>

---

#📍 Gerenciador de Pontos de Interesse (POI) com Geolocalização

![JavaScript](https://img.shields.io/badge/Frontend-JavaScript-F7DF1E?logo=javascript&logoColor=black)
![TailwindCSS](https://img.shields.io/badge/TailwindCSS-38B2AC?logo=tailwindcss&logoColor=white)
![License MIT](https://img.shields.io/badge/License-MIT-green)
![Status Stable](https://img.shields.io/badge/Status-Stable-success)
![Version 1.0.0](https://img.shields.io/badge/Version-1.0.0-blue)
![GitHub stars](https://img.shields.io/github/stars/NinoMiquelino/leaflet-poi-address-manager?style=social)
![GitHub forks](https://img.shields.io/github/forks/NinoMiquelino/leaflet-poi-address-manager?style=social)
![GitHub issues](https://img.shields.io/github/issues/NinoMiquelino/leaflet-poi-address-manager)

Este projeto é um aplicativo interativo de mapeamento focado em usabilidade e gerenciamento de dados geográficos. Ele combina a API de Geolocalização nativa do navegador para localizar o usuário com a poderosa biblioteca Leaflet.js para renderização de mapas.

O grande destaque é a integração com a Geocodificação Reversa (Nominatim), que transforma coordenadas de clique em endereços completos e legíveis, enriquecendo os Pontos de Interesse (POIs) salvos pelo usuário.

---

✨ Destaques do Projeto
 * Geocodificação Reversa (Nominatim): Converte coordenadas de Lat/Lng em endereços completos e formatados, exibindo-os tanto na localização do usuário quanto nos POIs salvos.
 * Geolocalização Automática: Utiliza a API nativa do navegador para encontrar e marcar a posição atual do usuário no mapa com um ícone dedicado.
 * Gerenciamento de POI: Permite que o usuário adicione pontos de interesse personalizados com nome, exibindo-os no mapa (com marcadores customizados) e listando-os em uma barra lateral interativa.
 * Design em Camadas: Uso eficiente de marcadores e ícones personalizados no Leaflet para diferenciar claramente a posição do usuário (azul) dos POIs salvos (amarelo).
 * Navegação Rápida: O clique em qualquer item da lista lateral centraliza o mapa instantaneamente no POI correspondente.

---

## 🧠 Tecnologias utilizadas
 * Framework de Mapa: Leaflet.js (CDN)
 * API de Geolocalização: API nativa do navegador (navigator.geolocation)
 * Geocodificação: API Nominatim (OpenStreetMap)
 * Frontend: HTML5, JavaScript Assíncrono (fetch, async/await) e Tailwind CSS (CDN).

---

## 🧩 Estrutura do Projeto

```
leaflet-poi-address-manager/
├── index.html
├── README.md
├── .gitignore
└── LICENSE
```

---

## ⚙️ Configuração e Instalação

Pré-requisitos
Nenhum pré-requisito. O projeto é executado inteiramente no lado do cliente e utiliza recursos gratuitos da web (CDNs e APIs públicas).
Execução
 * Salve o código fornecido como index.html.
 * Abra o arquivo index.html diretamente em qualquer navegador web moderno.
 * Atenção: O navegador solicitará permissão para acessar sua localização. É necessário permitir para que o recurso de "Localização do Usuário" funcione.

---

## 📝 Instruções de Uso

 * Localização Automática: Ao carregar, o mapa tentará encontrar sua posição e exibirá seu endereço completo no painel lateral.
 * Adicionar POI: Clique ou toque em qualquer lugar no mapa onde você deseja salvar um Ponto de Interesse.
 * Nomear: Uma caixa de diálogo pedirá o nome do POI (ex: "Casa do Amigo", "Farmácia").
 * Processamento: O aplicativo fará uma chamada de API para obter o endereço completo do local clicado.
 * Gerenciamento: O novo POI será adicionado à lista lateral com seu nome e endereço. Clicar no item da lista centraliza o mapa no POI.

---

## 🤝 Contribuições
Contribuições são sempre bem-vindas!  
Sinta-se à vontade para abrir uma [*issue*](https://github.com/NinoMiquelino/leaflet-poi-address-manager/issues) com sugestões ou enviar um [*pull request*](https://github.com/NinoMiquelino/leaflet-poi-address-manager/pulls) com melhorias.

---

## 💬 Contato
📧 [Entre em contato pelo LinkedIn](https://www.linkedin.com/in/onivaldomiquelino/)  
💻 Desenvolvido por **Onivaldo Miquelino**

---
