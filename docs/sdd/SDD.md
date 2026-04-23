# 🎧 SDD – Sound Design Document  
**Projeto:** Tower Defense (Roblox)

---

## 1. Finalidade do documento
Este documento apresenta a estrutura do design sonoro do jogo *Tower Defense*, descrevendo a utilização de trilhas musicais e efeitos sonoros, seus contextos de aplicação, eventos de acionamento e diretrizes para evolução futura.

---

## 2. Caracterização da proposta sonora
A proposta sonora está alinhada ao gênero estratégico em tempo real:

- Estabelecer ambientação de combate  
- Fornecer respostas imediatas ao jogador  
- Sinalizar mudanças no estado do jogo  
- Intensificar a percepção de progressão  

---

## 3. Propósitos do sistema de áudio

- Manter ambientação contínua  
- Reforçar ações estratégicas  
- Comunicar eventos críticos  
- Auxiliar na leitura do jogo  
- Permitir expansão do sistema  

---

## 4. Sistema de Áudio (- Link](docs/Sounds.md) )

### 4.1 Trilhas musicais

| Arquivo | Tipo | Aplicação |
|--------|------|----------|
| `/sound/ambience/medieval_music.wav` | Trilha sonora de fundo principal | Ambientação principal da partida |

---

### 4.2 Efeitos sonoros

| Arquivo | Tipo | Aplicação |
|--------|------|----------|
| `/sound/sfx/tower_placement.wav` | SFX | Posicionar torre no campo de batalha |
| `/sound/sfx/esqueletos.wav` | SFX | Morte dos esqueletos |
| `/sfx/golenpedra/wav.wav` | SFX | Destruição de golem de pedra |

---

## 5. Função dos componentes sonoros

- As trilhas caracterizam estados do jogo  
- Efeitos validam ações e eventos  
- Sinais sonoros orientam decisões do jogador  

---

## 6. Eventos de execução sonora

- **Menu:** música de menu  
- **Partida:** trilha de gameplay  
- **Onda:** som de início  
- **Torres:** efeitos de ação  
- **Vitória/Derrota:** trilhas específicas  

---

## 7. Sequência sonora da experiência

- Entrada no menu  
- Início da partida  
- Execução das ondas  
- Eventos críticos  
- Finalização e retorno  

---

## 8. Contribuição do áudio

- Confirma ações  
- Indica eventos  
- Aumenta imersão  
- Auxilia decisões  

---

## 9. Parâmetros de mixagem

- Priorizar efeitos importantes  
- Evitar sobreposição excessiva  
- Manter clareza sonora  

---

## 10. Padronização estética

- Coerência com o gênero  
- Sons diretos  
- Progressão sonora  

---

## 11. Restrições

- Pouca variação sonora  
- Sem áudio 3D  
- Controle limitado  

---

## 12. Melhorias futuras

- Áudio espacial  
- Trilhas dinâmicas  
- Mais variações sonoras  
- Controle de volume  

---

## 13. Considerações finais

O design sonoro atende aos requisitos básicos e permite expansão futura.
