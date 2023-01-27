const text = "Lorem ipsum dolor sit, amen consectetur adipisicing elit. ";
const base = document.getElementById("textArea");

const typeText = (txt, speed = 100) => {
  const myText = [...txt];
  let num = 0;
  const interval = setInterval(() => {
    base.innerHTML += myText[num] == " " ? "&nbsp;" : myText[num];
    num >= text.length - 1 ? clearInterval(interval) : num++;
  }, speed);
};

typeText(text, 100);
