# 🏰 Siege Of Crowns TD

Jogo Tower Defense com temática medieval desenvolvido no Roblox Studio, indicado para todas as idades. O jogador precisa posicionar três tipos de torres de ataque( gladiador, arqueira e canhão) ao longo do caminho e impedir que ondas de monstros cheguem ao vilarejo. Entre uma onda e outra, o jogador usa o dinheiro coletado para posicionar novas torres ou melhorar as que já estão no campo.



---

## 👥 Equipe

| Nome | Função |
|------|--------|
| Luís Guilherme | Programação e lógica do jogo |
| Pedro | Game Design |
| Emanuel e Gabriel Cardoso | Arte e cenários |
| Erick, Ítalo e Maria Eduarda| Trilha sonora e efeitos |
| Lucas e Rafael | Pesquisa e avaliação de impacto |
| Todos os integrantes | Documentação( GDD, SDD e Repositório) |
---

## 🎯 Objetivo do Pacote


Este repositório possui todos os assets, documentações e arquivos do jogo Tower Defense desenvolvido para as disciplinas do curso de Sistemas de Informação.

---

## 📂 Conteúdo por Categoria

### 🎵 Sons
Efeitos sonoros, música ambiente e feedbacks sonoros. 
No momento, temos sons apenas nos formatos WAV e OGG.
Música ambiente = música com temática medieval em loop.

### 🖼️ Cenário
Arquivos com os assets e modelagens de cenário.

### 📄 Docs
- [SDD - Sound Design Document](docs/sdd/SDD.md)
- [GDD - Game Desing Document] 


### 💻 Scripts
Scripts de colisão, configurações do jogo, sistema de moedas, spawn de mobs, animação de mobs, sistema de posicionamento das torres.
Todos feitos em linguagem Luau, a linguagem utilizada no Roblox Studio.

---

## 🛠️ Ferramentas Usadas

- **Engine/Framework:** Roblox Studio
- **Linguagem:** Luau
- **Áudios e edição:** OpenGameArt e Audacity
- **Versionamento:** Git + GitHub

---

## 🗂️ Estrutura do Projeto


```text
Siege-Of-Crowns/
├── main.py
├── README.md
│
├── docs/
│   ├── SDD/
│   │   └── SDD.md
│
├── Sons/
│   ├── Sounds.md
│
├── Cenário/
│   ├── Caverna.rbxm
│   ├── Cenário.rbxm
│   ├── Mapa.rbxm
│   ├── Montanhas.rbxm
│   ├── Waypoints.rbxm
│   ├── Mobs.rbxm
│   └── Towers.rbxm
│
├── scripts/
│   ├── CollisionConfig.luau
│   ├── GameConfig.luau
│   ├── GladiatorCollisionSetup.luau
│   ├── FixPlayerScale.luau
│   ├── GoldCount.luau
│   ├── GoldLeaderboard.luau
│   ├── MobAnimations.luau
│   └── Main.rbxmx
```

---

## 🔗 Observações de Integração

Os scripts .luau localizados em scripts/ são executados dentro do ambiente Roblox e dependem diretamente dos modelos .rbxm da pasta Cenário/ — por exemplo, CollisionConfig.luau e GladiatorCollisionSetup.luau referenciam os objetos de colisão dos cenários, enquanto MobAnimations.luau depende de Mobs.rbxm e GoldCount.luau / GoldLeaderboard.luau interagem com a lógica de jogo orquestrada por Main.rbxmx. O arquivo main.py atua como ponto de entrada externo ao Roblox, para automação e configuração do ambiente. A documentação em docs/SDD/SDD.md deve refletir qualquer alteração feita nos scripts ou modelos, e os assets de som referenciados em sons/Sounds.md estarão devidamente vinculados aos scripts que os acionam dentro do jogo.

---

## 📚 Disciplina

- **Curso:** Sistemas de Informação  
- **Disciplina:** Desenvolvimento, design e sons em jogos digitais 
- **Professores:** Arly Alves e Rodrigo de Carvalho
- **Instituição:** União Pioneira de Integração Social ( UPIS )
---
