# 貝茲曲線
## 歷史
是計算機圖形學中相當重要的參數曲線，於1962年由法國工程師皮埃爾·貝茲（Pierre Bézier）所廣泛發表，他運用貝茲曲線來為汽車的主體進行設計
## 數學原理
一條貝茲曲線由數個控制點組成，若一曲線給定 <img src="http://latex.codecogs.com/svg.latex?n+1"/> 個控制點
<br><br>
<img src="http://latex.codecogs.com/svg.latex?P_{0}, P_{1}, \cdots , P_{n}" />
<br><br>
則可隨著時間 <img src="http://latex.codecogs.com/svg.latex?t\in [0, 1]" /> 繪製出曲線，而在時刻 <img src="http://latex.codecogs.com/svg.latex?t"/> 時繪製的點座標為
<br><br>
<img src="http://latex.codecogs.com/svg.latex?\sum_{i=0}^{n}\binom{n}{i}t^{i}(1-t)^{n-i}P_{i}" />
<br><br>
一條 <img src="http://latex.codecogs.com/svg.latex?n+1=5" /> 的貝茲曲線示意圖
<br><br>
<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/0/0b/BezierCurve.gif/240px-BezierCurve.gif" />
