# 🐱 O Resgate do Gato Mago: O Despertar do Sonho

Este projeto é uma experiência imersiva de Realidade Virtual desenvolvida com o framework **A-Frame**. O trabalho consiste em um jogo de aventura e puzzle onde o jogador deve navegar por uma dimensão fantasiosa para libertar um mestre felino de uma prisão mágica.

## Alunos
* Nikoly Cover Pereira
* Vinicius de Oliveira Jimenez

## Sobre o Trabalho
O Reino dos Sonhos foi invadido por uma névoa densa e escura. O **Gato Mago**, protetor da aurora, foi aprisionado por fragmentos de pesadelo. Através de uma narrativa lúdica, o jogador deve interagir com o ambiente para restaurar a luz e realizar o ritual de libertação.

### As Etapas do Desafio:
1.  **A Caça às Sombras:** O jogador precisa localizar e capturar **3 Sombras Errantes** (esferas volantes) que protegem a jaula.
3.  **O Ritual Alquímico:** No altar final, é necessário misturar três essências no caldeirão seguindo a ordem exata: **Verde -> Rosa -> Azul**. Caso o jogador erre a sequência, o sonho colapsa e o ritual deve ser reiniciado.

## Controles

### No Computador (Teclado e Mouse):
* **W, A, S, D:** Movimentação pelo cenário.
* **Mouse:** Olhar para os lados (Câmera).
* **Clique Esquerdo:** Interagir com objetos (Mago, Livro, Cristais e Poções).

### No Meta Quest (VR):
* **Gatilho (Trigger):** Apontar o laser e clicar para coletar e interagir com os elementos.

## Como Executar o Projeto

Como o projeto utiliza o framework A-Frame, ele roda diretamente no navegador, mas devido ao carregamento de modelos 3D (`.glb`), é necessário um servidor local para evitar erros de política de segurança (CORS).

### Passo a Passo:
1.  Certifique-se de que o arquivo HTML e os modelos 3D estão na mesma pasta.
2.  Inicie um servidor local. Você pode usar a extensão "Live Server" do VS Code.
3.  Acesse o endereço (geralmente `http://localhost:5500`) em um navegador moderno (Chrome, Edge ou Firefox).
4.  Para testar no **Meta Quest**, acesse o endereço IP da máquina através do navegador do óculos (ex: `http://192.168.0.x:5500`).

## Tecnologias e Recursos
* **A-Frame:** Framework para experiências 3D e VR.
* **A-Frame Environment Component:** Criação do bioma "Dream".
* **JavaScript (ES6):** Lógica de estados, inventário e interações.
* **Modelos 3D:** Formato `.glb` para personagens e itens.
