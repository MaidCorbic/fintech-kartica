# Fintech Kartica — Interaktivni Demo

**Interaktivna digitalna kartica u HTML, CSS i JavaScriptu sa realističnim 3D efektima, automatskom promjenom boja po brendu kartice, flip animacijom za CVV, maskiranjem broja i mogućnošću preuzimanja kartice kao JPG. 
Idealan demo za fintech projekte, UI/UX eksperiment ili edukativni prikaz modernih web tehnologija.**

---

## 🎯 Feature-i projekta

- Automatska promjena boja i pozadina kartice prema brendu (Visa, MasterCard, Amex, Maestro)  
- Flip kartice za prikaz CVV/CVC  
- Tilt i hover efekt za realističan 3D osjećaj  
- Maskiranje broja kartice za sigurnost  
- Dugme za preuzimanje kartice kao JPG sliku  
- Greeting banner pri učitavanju stranice (“Dobrodošli u Vašu Digitalnu Banku”)  
- Responsive dizajn, radi na svim veličinama ekrana  

---

## 💻 Kako koristiti

1. Otvori [Live demo](https://USERNAME.github.io/fintech-kartica/)  
2. Unesi ime i prezime  
3. Unesi broj kartice (automatski prepoznaje brend i mijenja boje)  
4. Unesi datum i CVV  
5. Klikni na karticu za flip animaciju  
6. Klikni na dugme "💾 Sačuvaj karticu kao JPG" za preuzimanje  

---

## 📌 Primjer HTML koda kartice

```html
<div class="scene">
  <div class="card" id="card">
    <div class="side front">
      <div class="number" id="cardNumber"></div>
      <div class="bottom">
        <div id="cardName"></div>
        <div class="brand" id="cardBrand"></div>
      </div>
    </div>
    <div class="side back">
      <div class="strip"></div>
      <div class="cvv">CVV: <span id="cardCVV"></span></div>
    </div>
  </div>
</div>
