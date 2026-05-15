const yes = document.querySelector("#yes");
const no = document.querySelector("#no");
const gif = document.querySelector("#gif");
const text = document.querySelector("#text");
const vid = document.querySelector("video");
let count = 2;

// ✅ use ROOT-relative paths
const gifs = [
  "resources/cat-heart.gif",
  "resources/rusure.gif",
  "resources/3shocked-1.gif",
  "resources/4.crying.gif",
  "resources/5.crying.gif",
  "resources/idc.gif"
];

// preload gifs
gifs.forEach(src => {
  const img = new Image();
  img.src = src;
});

no.addEventListener("click", () => {
  if (count === 2) {
    gif.src = "resources/rusure.gif";
    text.innerHTML = "You meant to press YES right?🤨";
    yes.style.height = "65%";
    yes.style.width = "60%";
    no.style.width = "30%";
    count++;
  } 
  else if (count === 3) {
    gif.src = "resources/3shocked-1.gif";
    text.innerHTML = "Your hand must have slipped right?🥹";
    yes.style.height = "70%";
    yes.style.width = "70%";
    no.style.width = "20%";
    count++;
  } 
  else if (count === 4) {
    gif.src = "resources/4.crying.gif";
    text.innerHTML = "I'm gonna cry😭";
    yes.style.height = "80%";
    yes.style.width = "80%";
    no.style.fontSize = "4vh";
    no.style.width = "10%";
    count++;
  } 
  else if (count === 5) {
    gif.src = "resources/5.crying.gif";
    text.innerHTML = "Pretty Please🥺😘";
    yes.style.height = "90%";
    yes.style.width = "96%";
    no.style.display = "none";
  }
});

yes.addEventListener("click", () => {
  vid.style.display = "block";
  gif.src = "resources/idc.gif";
  text.innerHTML = "I knew it 😘 I love you <3";

  yes.innerHTML = `<a href="@Jsiheowuwjw" target="_blank">Message for me</a>`;
  yes.style.height = "90%";
  yes.style.width = "96%";
  no.style.display = "none";

  setTimeout(() => {
    vid.style.display = "none";
  }, 9000);
});
