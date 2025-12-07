# 📂 Manifolds
(Topological subspaces for ludic experimentation.)

Este diretório atua como o catálogo taxonômico do repositório, classificando projetos, protótipos de Game Jams e provas de conceito com base na sua dimensão espacial e topologia de renderização.

Enquanto a Fnord Dynamics calcula as forças e o Gambit Engine projeta os pixels, é dentro dos Manifolds que essas tecnologias convergem para criar experiências interativas concretas.

---

## 🗂️ Estrutura Taxonômica

Os projetos são segregados pela natureza do seu espaço vetorial:

- flatland/ (2D Euclidean)
Projeções bidimensionais estritas.

Foco: Sprites, UI, Shaders de Pixel, Autômatos Celulares Planos.

Engine Profile: Gambit 2D Renderer (Orthographic Camera).

- voxels/ (2.5D / Discrete 3D)
Espaços volumétricos discretos ou projeções isométricas.

Foco: Grids táticos, Raymarching, Estética Low-Poly, Estruturas de Dados Octree.

Engine Profile: Hibridismo (Física Fnord discreta + Render Gambit Isométrico).

- hyperreal/ (3D Continuous)
Simulações tridimensionais de alta fidelidade e continuum mechanics.

Foco: PBR (Physically Based Rendering), Cinemática Inversa (IK), Fluidos, Iluminação Global.

Engine Profile: Fnord Dynamics (High-Dim Solver) + Gambit (Perspective Camera).

- abstract/ (Non-Euclidean / n-Dimensional)
Experimentos que desafiam a geometria convencional.

Foco: Geometria Hiperbólica, Visualização de 4D+, Espaços Recursivos.

Engine Profile: Uso intensivo do namespace HodgePodge para projeções matemáticas experimentais.

---

## 🔗 Integração de Sistemas
Cada projeto listado nestas subpastas serve como um caso de teste ("Testbed") para os módulos centrais:

- Ingestão: Consomem dados físicos da fnord_dynamics.

- Projeção: Renderizam o estado via gambit_engine.

- Feedback: Retornam métricas de performance e bugs lógicos para a _knowledge_base.
