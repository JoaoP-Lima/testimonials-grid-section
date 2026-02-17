
# Frontend Mentor | Testimonials Grid Section
![Design preview for the Testimonials grid section coding challenge](./preview.jpg)



## 📄 Sobre o Projeto

Seção de **depoimentos de alunos** responsiva com cards contendo:

- Foto do usuário
- Nome e status
- Citação / depoimento
- Aspas decorativas em background

O layout é inspirado no Figma do desafio Frontend Mentor e utiliza **CSS Grid e Flexbox**.

---

## 🛠 Tecnologias

- HTML5  
- CSS3  
- Google Fonts: *Barlow Semi Condensed*  
- CSS Grid & Flexbox  
- `clamp()` para fontes responsivas  
- Transições para hover suave  

---

## 📐 Layout e Responsividade

**Mobile-first**:  

- **Mobile (≤ 767px):** 1 coluna, cards empilhados  
- **Tablet (768px – 1199px):** 2 colunas  
- **Desktop (≥ 1200px):** 4 colunas  

Exemplo de grid para tablet:

```css
.testimonials-cards {
  display: grid;
  grid-template-columns: repeat(2, 1fr);
  grid-template-areas:
    "card1 card1"
    "card2 card4"
    "card5 card5"
    "card3 card3";
  gap: 32px;
}