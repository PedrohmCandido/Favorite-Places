# 🌍 Place Picker

Crie sua coleção personalizada de lugares que você deseja visitar!  
Este projeto é uma galeria interativa onde o usuário pode escolher destinos turísticos, ver os mais próximos com base em sua localização atual e gerenciar sua lista com confirmação e persistência de dados.

---

## 🚀 Descrição

O **Place Picker** permite que usuários selecionem lugares que gostariam de visitar. A lista é salva no **localStorage**, garantindo persistência mesmo ao recarregar a página. Os locais disponíveis são embaralhados dinamicamente de acordo com a **localização geográfica do usuário**, exibindo os destinos mais próximos primeiro. A exclusão de itens da lista é feita com um **modal de confirmação com temporizador**, oferecendo uma interface segura e fluida.

---

## 🎯 Funcionalidades

- 🧭 Detecta a localização do usuário e ordena os lugares por proximidade
- 📌 Seleção de destinos turísticos
- 💾 Armazenamento local com `localStorage`
- 🧹 Exclusão com confirmação via modal
- 📊 Barra de progresso visual dos lugares selecionados
- 🔄 Lista embaralhada dinamicamente
- 🎯 Interface visual com imagens atrativas

---

## 🛠 Tecnologias Utilizadas

- ⚛️ **React.js**
- 🎯 **Hooks**: `useState`, `useRef`, entre outros
- 🌐 API de localização via `navigator.geolocation`
- 💅 **CSS** puro para estilização

---

## 📂 Estrutura do Projeto

```bash
src/
├── assets/                # Imagens e recursos estáticos
├── components/            # Componentes reutilizáveis
│   ├── DeleteConfirmation.jsx
│   ├── Modal.jsx
│   ├── Places.jsx
│   └── ProgressBar.jsx
├── App.jsx                # Componente principal
├── data.js                # Dados dos lugares
├── loc.js                 # Funções de localização
├── index.css              # Estilos globais
└── main.jsx               # Ponto de entrada da aplicação
```

---

## 💻 Como Rodar o Projeto Localmente

1. Clone o repositório:
   ```bash
   git clone https://github.com/PedrohmCandido/placepicker.git
   cd placepicker
   ```

2. Instale as dependências:
   ```bash
   npm install
   ```

3. Rode o servidor de desenvolvimento:
   ```bash
   npm run dev
   ```

4. Acesse no navegador:
   ```
   http://localhost:5173
   ```

---

## 🔒 Licença

Este projeto está licenciado sob a **MIT License**.  
Sinta-se livre para usar, modificar e compartilhar! 🚀

---

## 📸 Imagens do Projeto

### Página principal

![Captura de tela 2025-04-29 162840](https://github.com/user-attachments/assets/a10a8413-2f88-4ec3-b92b-e988eb7d29b4)

### Lista personalizada

![Captura de tela 2025-04-29 163125](https://github.com/user-attachments/assets/1ce283d7-0c8a-442e-877c-d6700ba4d733)

### Modal de exclusão

![Captura de tela 2025-04-29 163211](https://github.com/user-attachments/assets/41e1bbd1-4df9-4f6f-9e38-78b730dbd2b1)


## 🌐 Links Importantes

- 🔗 **Repositório GitHub:** [github.com/seu-usuario/placepicker](https://github.com/PedrohmCandido/Place-Picker)
- 🔗 **Demo Online:** https://favorite-places-lake.vercel.app/

