# My Project
let coins = 0;

function addCoin() {
  coins++;
  document.getElementById("coins").textContent = coins;
}

function resetCoins() {
  coins = 0;
  document.getElementById("coins").textContent = coins;
}
