# plann.er 🌍✈️
 <P>
     <img src="https://raw.githubusercontent.com/Whuanderson/NLW-Journey/refs/heads/main/.github/Aceitar%20convite.png" alt="Convite" width="260"/>
  <img src="https://raw.githubusercontent.com/Whuanderson/NLW-Journey/refs/heads/main/.github/Atividades.png" alt="Atividades" width="260"/>
  <img src="https://raw.githubusercontent.com/Whuanderson/NLW-Journey/refs/heads/main/.github/Detalhes%20da%20Viagem.png" alt="Detalhes da Viagem" width="260"/>     
 </P>
    <img src="https://raw.githubusercontent.com/Whuanderson/NLW-Journey/refs/heads/main/.github/Nova%20Viagem.png" alt="Nova Viagem" width="460"/>


Aplicativo mobile para **planejar viagens, convidar amigos e gerenciar cada detalhe do roteiro**, criado durante a **NLW – Journey** da Rocketseat.

---

## ✨ Funcionalidades

- **Adicionar viagem**: destino, datas de ida e volta  
- **Convites por e‑mail** para amigos participarem  
- **Lista de atividades** e notas da viagem  
- **Persistência** local e sincronização com back‑end (trilha Node.js)  

---

## 🛠️ Tecnologias

- React Native + Expo  
- TypeScript  
- `react-native-calendars` + `dayjs`  
- Zustand (estado global)  
- Tailwind / NativeWind  
- Componentes customizados  

---

## 📦 Estrutura

```
src
 ├─ assets        # imagens e ícones
 ├─ components    # Button, Input, Modal, etc.
 ├─ screens       # telas do app
 ├─ storage       # helpers AsyncStorage
 ├─ server        # chamadas à API
 └─ utils         # helpers (validações, datas)
```

---

## 🚀 Instalação

> Requer **Node.js** e **Expo CLI** (`npm install -g expo-cli`).

```bash
# clone
git clone https://github.com/Whuanderson/NLW-Journey.git
cd NLW-Journey

# dependências
npm install       # ou yarn
```

```bash
# iniciar
npx expo start    # abre Expo DevTools
```

> Ajuste a URL da API em `src/server` para o IP da máquina que roda o back‑end.

---

## 📝 Licença

Distribuído sob licença **MIT**. Veja [LICENSE](LICENSE) para detalhes.

<p align="center">
  Feito por <a href="https://github.com/Whuanderson">Whuanderson Marinho</a> — deixe uma ⭐️ se curtir!
</p>
