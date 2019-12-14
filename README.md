# 貝茲曲線
## 歷史
是計算機圖形學中相當重要的參數曲線，於1962年由法國工程師皮埃爾·貝茲（Pierre Bézier）所廣泛發表，他運用貝茲曲線來為汽車的主體進行設計
## 數學原理
一條貝茲曲線由數個控制點組成，若一曲線給定 <img src="http://latex.codecogs.com/svg.latex?n+1"/> 個控制點
<br><br>
<img src="http://latex.codecogs.com/svg.latex?P_{0}, P_{1}, \cdots , P_{n}" />
<br><br>
則該曲線表示為
<br><br>
<img src="http://latex.codecogs.com/svg.latex?\sum_{i=0}^{n}\binom{n}{i}t^{i}(1-t)^{n-i}P_{i}" />
<br><br>
其中 <img src="http://latex.codecogs.com/svg.latex?t" /> 代表時間，即曲線由起點 <img src="http://latex.codecogs.com/svg.latex?t=0" border="0" /> 到終點 <img src="http://latex.codecogs.com/svg.latex?t=1" />
