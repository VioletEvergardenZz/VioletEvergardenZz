// 创建一个 SVG 元素
const svg = document.createElementNS("http://www.w3.org/2000/svg", "svg");
svg.setAttribute("width", "435");
svg.setAttribute("height", "28");

// 创建文本元素
const text = document.createElementNS("http://www.w3.org/2000/svg", "text");
text.setAttribute("font-family", "Fira Code");
text.setAttribute("font-size", "24");
text.setAttribute("x", "10");
text.setAttribute("y", "20");
text.textContent = "你好，世界";

// 将文本元素添加到 SVG 中
svg.appendChild(text);

// 将 SVG 转换为字符串并添加到 README 中
const svgString = encodeURIComponent(new XMLSerializer().serializeToString(svg));
const typingSVG = `![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&pause=200&width=435&height=28&lines=${svgString})`;



## Languages and Tools
[![My Skills](https://skillicons.dev/icons?i=py,bash,linux,ubuntu,vscode,docker,kubernetes,git&theme=light)](https://skillicons.dev)

![python](https://img.shields.io/badge/-python-%233776AB?style=flat&logo=python&logoColor=ffffff)
![Shell](https://img.shields.io/badge/-Shell-%2389E051?style=flat&logo=powershell&logoColor=ffffff)
![Linux](https://img.shields.io/badge/-Linux-%23FCC624?style=flat&logo=linux&logoColor=ffffff)
![Ubuntu](https://img.shields.io/badge/-Ubuntu-%23E95420?style=flat&logo=ubuntu&logoColor=ffffff)
![VS Code](https://img.shields.io/badge/-VSCode-%230066B8?style=flat&logo=visual-studio-code&logoColor=ffffff)
![Docker](https://img.shields.io/badge/-Docker-%232496ED?style=flat&logo=docker&logoColor=ffffff)
![Kubernetes](https://img.shields.io/badge/-Kubernetes-%23326CE5?style=flat&logo=kubernetes&logoColor=ffffff)
![Git](https://img.shields.io/badge/-Git-%23ED5A47?style=flat&logo=git&logoColor=%23ffffff)

![GitHub账户最常用语言](https://github-stats.ubrong.com/api/top-langs/?username=VioletEvergardenZz&layout=compact&theme=tokyonight) 

