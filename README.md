# Сute mold
Mold grow and evolution simulation. The mold gets energy for the void space around it, so the mold that has more void will survive. Molds cannot interact or damage each other, evolutionary selection goes only by competing for space.

Molds with the same genome have the same color, but different shades. Mold with a mutated genome get a new color. Cells with black dots are spores. 

Press G to generate new molds. Press Q/W to lessen/expand the amount of energy. Press P to pause.

Left-click on the mold to copy genome to clipboard. Click on the void space to create a new mold with the genome saved to your clipboard.

![image](https://user-images.githubusercontent.com/108512083/177539565-39ab3136-3d84-47aa-900e-3da9efcd708f.png)
![image](https://user-images.githubusercontent.com/108512083/177507626-4a31e661-5aef-4326-80cc-6e43719566d7.png)

---

Requires [ebiten](https://github.com/rxi/lume) and [clipboard](github.com/atotto/clipboard). Thanks for making them!
```
go get github.com/atotto/clipboard
go get github.com/hajimehoshi/ebiten/v2
```
