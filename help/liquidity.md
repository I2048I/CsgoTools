# Liquidity

中文[点这里](https://github.com/I2048I/CsgoTools/blob/main/help/liquidity_SC.md)

Liquidity is one of the characteristics of Csgo Quantitative Tool. By observing the size of liquidity value, the screening value of the jewelry can be analyzed.

The calculation part includes the number of selling orders of jewelry platforms, and the main formula is `Math.log(rarity) / Math.log(sellNum * buyNum)`

The specific color of liquidity is as follows

Liquidity | Color
---- | ----- 
x>=15 | ![#228B22](https://via.placeholder.com/15/228B22/000000?text=+) #228B22
12<x<15 | ![#3CB371](https://via.placeholder.com/15/3CB371/000000?text=+) #3CB371
10<x<=12 | ![#32CD32](https://via.placeholder.com/15/32CD32/000000?text=+) #32CD32
7<x<=10 | ![#90EE90](https://via.placeholder.com/15/90EE90/000000?text=+) #90EE90
5<x<=7 | ![#000000](https://via.placeholder.com/15/000000/000000?text=+) #000000
3<x<=5 | ![#F08080](https://via.placeholder.com/15/F08080/000000?text=+) #F08080
x<=3 | ![#8B0000](https://via.placeholder.com/15/8B0000/000000?text=+) #8B0000

### Notice

1. This data will cause errors due to the number of ornaments on the platform, and will lead to larger errors if large merchants sweep goods in large quantities.

2. Liquidity is only calculated by analyzing the above three dimensions, which is for reference only and does not constitute investment advice.
