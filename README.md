# 🎄 Mercado de Natal de Santar — Mapa Interativo  
*(Christmas Market of Santar — Interactive Map)*

Bem-vindo ao **Mapa Interativo do Mercado de Natal de Santar**!  
Este projeto mostra o percurso completo do mercado, com pontos de interesse, descrições em português e funcionalidades interativas — perfeito para visitantes que usam o QR code durante o evento.

Welcome to the **Interactive Map of the Santar Christmas Market**!  
This project displays the full walking route of the market, with festive points of interest, Portuguese descriptions, and interactive features — perfect for visitors using the QR code during the event.

---

## ✨ Funcionalidades / Features

- 🗺️ **Mapa interativo** baseado em [Leaflet](https://leafletjs.com/)  
  *Interactive map powered by Leaflet*
- 📍 **Localização em tempo real** (botão “A minha localização”)  
  *Live location tracking (“My location” button)*
- 🧭 **Botão “Ir para o início do mercado”** — desenha uma rota a pé desde a posição atual até à entrada  
  *“Go to Market Start” button — draws a walking route from your location to the entrance*
- 📱 **Botão “QR do mapa”** — mostra um código QR para partilhar o link  
  *“QR of the Map” button — generates a QR code for sharing the map*
- 🧡 **Botões de locais** — cada um abre o marcador correspondente e mostra a descrição  
  *Clickable location list — opens the related marker and popup description*
- 🎅 **Favicon festivo** (árvore de Natal)  
  *Festive favicon (Christmas tree)*
- 🔁 **Percurso circular completo** pelo centro de Santar  
  *Circular walking route through the heart of Santar*

---

## 📍 Ponto de Início / Fim  
**Rua do Estremadouro** — (40.5709815, -7.8907183)

---

## 📖 Como usar / How to use

### A) Para visitar o mapa / To visit the map
1. Aceda a:  
   👉 [https://nevessusie.github.io/mercadodesantar/](https://nevessusie.github.io/mercadodesantar/)
2. Permita a localização se for pedido (para ver a sua posição).  
   *Allow location when prompted to see your live position.*
3. Explore os pontos clicando nos botões à esquerda.  
   *Explore the route by tapping the location buttons.*

### B) Para editar / maintain the project
1. Clone ou descarregue este repositório:  
   ```bash
   git clone https://github.com/nevessusie/mercadodesantar.git
Edite o ficheiro index.html conforme necessário:
Atualize descrições ou coordenadas
Adicione novos pontos de interesse
Substitua o favicon.png se quiser um novo ícone
Faça commit e push das alterações:

git add .
git commit -m "Atualização do mapa"
git push

🖼️ Estrutura / Project Structure

mercadodesantar/
├── index.html        # Página principal / main interactive map
├── favicon.png       # Ícone / favicon (Christmas tree)
└── README.md         # Este ficheiro / this file

🌐 Publicação / Deployment
O site é publicado através do GitHub Pages:
The site is hosted via GitHub Pages:
Branch: main
Pasta / Folder: / (root)
As alterações são aplicadas automaticamente cerca de 1 minuto após o commit.
Changes go live automatically within ~1 minute after committing.

🧩 Tecnologias usadas / Technologies used
Tecnologia	Descrição
Leaflet	Mapa interativo / Interactive mapping library
OpenStreetMap	Dados cartográficos / Map data
Leaflet Routing Machine	Rotas a pé / Walking routes
Leaflet LocateControl	Localização do utilizador / User geolocation
QRCode.js	Geração de QR codes / QR code generation

🪪 Licença / License
Este projeto é open-source sob a licença MIT.
Pode ser livremente utilizado, modificado e partilhado para fins não comerciais ou comunitários.
This project is open-source under the MIT License.
You’re free to use, modify, and share it for non-commercial or community purposes.

🎁 Agradecimentos / Acknowledgments
Projeto criado para o Mercado de Natal de Santar, Portugal,
para tornar o percurso mais mágico, interativo e acessível a todos os visitantes. 🎄✨
Created for the Santar Christmas Market, Portugal,
to make the visitor experience more magical, interactive, and accessible for everyone. 🎅✨
