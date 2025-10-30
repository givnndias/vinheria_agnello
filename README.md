### **Projeto Vinheria Merlot – Portal de E-commerce**

*Um projeto acadêmico que traduz a experiência calorosa e o atendimento consultivo de uma vinheria tradicional para o universo digital.*

---

📝 **Resumo do Projeto**

Este é um projeto acadêmico desenvolvido para o curso de Engenharia de Software da FIAP.Ele aborda o desafio de criar um portal de e-commerce para a **Vinheria Merlot**, uma empresa fictícia inspirada no estudo de caso "O Caso da Vinheria Agnello". O objetivo central é construir uma plataforma digital que não apenas venda vinhos, mas que também replique a atmosfera de confiança e o atendimento personalizado que são os grandes diferenciais da loja física.

---

🎯 **O Desafio: A Vinheria Agnello**

O projeto parte de um cenário detalhado, onde uma vinheria familiar e bem-sucedida enfrenta as barreiras do mundo digital.
**Gestão Tradicional:** O proprietário, Sr. Giulio, sempre resistiu à ideia de um e-commerce, por considerá-lo um meio "frio" e impessoal, incompatível com o padrão de atendimento que oferece.
**O Impacto da Pandemia:** As restrições de mobilidade durante a pandemia impactaram o negócio significativamente, forçando a empresa a repensar sua estratégia e a considerar a criação de um canal de vendas online.
**O Cliente Principal:** A grande maioria do público da vinheria é formada por iniciantes, que dependem do auxílio dos vendedores para escolher o vinho ideal para cada ocasião.
**O Objetivo Central:** O maior desafio é claro: "É possível reproduzir essa experiência de compra no mundo virtual?". A solução precisa oferecer uma experiência próxima à encontrada na loja física, mantendo o caráter consultivo e acolhedor.

---

💡 **A Solução: Website Vinheria Merlot**

Como resposta a este desafio, o website da **Vinheria Merlot** foi concebido para ser mais do que uma loja virtual. Ele é a porta de entrada digital para o universo da marca, construído sobre os seguintes pilares:
**Conteúdo Educativo:** Para atender ao público iniciante, a página inicial já oferece uma tabela detalhada de vinhos. Essa funcionalidade simula o papel do vendedor especialista, orientando o cliente sobre uvas, características e harmonizações.
**Construção de Confiança:** Através da seção "Quem Somos", o site conta a história da empresa, criando uma conexão emocional e combatendo a "frieza" do ambiente online que tanto preocupava o Sr. Giulio.
**Relacionamento com o Cliente:** O formulário de cadastro não é apenas para ofertas, mas uma ferramenta para entender as preferências do cliente e iniciar um relacionamento duradouro, oferecendo conteúdo e promoções personalizadas.

🚀 **Funcionalidades Implementadas (`index.html`)**

* **Header e Navegação:** Um cabeçalho com o logo da empresa e um menu de navegação claro para as futuras seções do site.
* **Seção "Quem Somos":** Uma introdução à história e paixão da vinheria, estabelecendo a identidade da marca.
* **Tabela de Vinhos:** Um guia prático e visual sobre os principais tipos de vinhos e suas combinações, funcionando como um "consultor digital".
* **Convite para Visita:** Uma seção que reforça a existência do espaço físico, convidando os usuários para uma experiência presencial e humanizando a marca.
* **Formulário de Cadastro:** Uma área interativa para capturar leads e segmentar clientes de acordo com suas preferências de vinho.

✨ **Efeitos Visuais (Checkpoint 02)**  

🎯 **Pseudo-classes aplicadas**  
* **:hover —** aplicada em botões, imagens e formulários, gerando efeitos de destaque com transições suaves.  
* **:focus —** usada em `input` e `textarea` para indicar o campo ativo, com borda e sombra em tom vinho.  
* **:active —** aplicada em links (`a:active`) para alterar a cor no momento do clique.  

🎨 **Pseudo-elementos aplicados**  
* **::selection —** muda a cor do fundo e do texto ao selecionar parágrafos (`p::selection`).  
* **::placeholder —** estiliza o texto dos campos de formulário, reforçando a identidade visual da vinheria.  

💫 **Animações e transições**  
* **Animação “descubra” (`@keyframes descubra`)**  
  Aplicada à classe `.animacao_produtos`, cria um efeito de transição suave de opacidade, simulando um “piscar” contínuo.  
  **Propriedades:** `animation-duration: 3s; animation-iteration-count: infinite;`  

* **Transições suaves:**  
  Utilizadas em imagens, botões e containers, com efeitos de cor, sombra e transformação (`transition: 0.3s–0.4s ease`).  

🎢 **Transformações CSS**  
* **scale() —** aplicado em imagens e botões, aumentando levemente o tamanho no `hover`.  
* **rotate() —** usado em ícones do rodapé, criando um efeito de rotação sutil.  
* **translateY() —** aplicado em `.info-contato:hover`, movendo o card levemente para cima.  

🛠️ **Tecnologias**

* **HTML:** Utilizado para a estruturação semântica de todo o conteúdo.
* **CSS:** Responsável pela estilização visual, identidade e layout da página.

👥 **Autores**

* Giovanna Oliveira Ferreira Dias;
* Marianne Mukai Nishikawa;
* Maria Laura Pereira Druzeic.

🔗 **Link para o site no GitHub Pages**
* https://givnndias.github.io/vinheria_agnello/
