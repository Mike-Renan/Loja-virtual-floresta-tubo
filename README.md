# Loja Virtual Floresta Tubo

E-commerce simples desenvolvido em **HTML, CSS e JavaScript** para a empresa **Floresta Tubos & Perfis**, com foco em UI/UX, SEO e finalização de pedidos via **WhatsApp**.

---

## 📌 Descrição

Este projeto é uma loja virtual voltada para a comercialização de produtos de ferro e aço (tubos, perfis, vigas, chapas, telas e acessórios).  
O objetivo é oferecer uma experiência simples e direta para o usuário:

- Navegar pelas categorias de produtos.  
- Adicionar itens ao carrinho (sem preço).  
- Finalizar o pedido diretamente pelo WhatsApp da loja.  

---

## 🚀 Funcionalidades

- **Seções principais:** Sobre, Produtos e Contatos.  
- **Carrinho de compras:** adiciona produtos com quantidade, permite limpar e editar.  
- **Finalização via WhatsApp:** gera mensagem automática com os itens selecionados.  
- **Filtros de produtos:** por categoria (Tubos, Perfis, Vigas, Telas, Portões, Acessórios).  
- **Design responsivo:** adaptado para desktop e mobile.  
- **SEO básico:** meta tags, dados estruturados (JSON-LD), títulos e descrições otimizadas.  
- **UI/UX:** feedback visual, botões acessíveis, foco visível, layout limpo e consistente.  

---

## 🛠️ Tecnologias Utilizadas

- **HTML5** → Estrutura semântica das páginas.  
- **CSS3** → Estilização com paleta de cores inspirada no site institucional.  
- **JavaScript (ES6+)** → Lógica do carrinho, filtros e integração com WhatsApp.  
- **Font Awesome** → Ícones para categorias e botões.  

---

## 📂 Estrutura de Pastas

/loja-virtual-floresta-tubo ├── index.html # Página principal ├── style.css # Estilos globais ├── script.js # Lógica do carrinho e WhatsApp └── assets/ # Imagens e ícones dos produtos

Código

---

## 📸 Exemplos de Produtos

- Tubo redondo  
- Tubo quadrado  
- Tubo retangular  
- Perfis dobrados  
- Vigas I e U  
- Portão basculante (kits e peças avulsas)  
- Telas onduladas  
- Acessórios e ferragens  

---

## ⚙️ Como Executar

1. Clone o repositório:
   ```bash
   git clone https://github.com/Mike-Renan/-loja-virtual-floresta-tubo.git
Acesse a pasta do projeto:

bash
cd -loja-virtual-floresta-tubo
Abra o arquivo index.html no navegador.

📱 Finalização via WhatsApp
O carrinho gera automaticamente uma mensagem com os itens selecionados e abre o WhatsApp Web ou aplicativo:

js
const url = `https://wa.me/${numeroWhatsApp}?text=${encodeURIComponent(mensagem)}`;
window.open(url, "_blank");
📈 Melhorias Futuras
Implementar sistema de login e cadastro.

Adicionar preços e cálculo automático de frete.

Painel administrativo para gestão de produtos.

Integração com meios de pagamento online.
