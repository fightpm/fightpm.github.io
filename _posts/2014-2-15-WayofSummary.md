---
layout: post
title: 計測した作業時間の要約方法
---

2014-2-15  
計測した作業時間を、新たな作業に必要な時間の見積もりに活用できるように、要約しておきます。
Excelなどのスプレッドシートを使って、アクティビティの種類ごとに、計測した作業時間を一覧表にします。  
・記録時間  
・開始  
・終了  
・コメント  
この表に作業の規模と生産性を追加します。  
・規模  
・生産性  
生産性の平均値、最大値、最小値を計算します。

規模の尺度はドキュメントならページ数、プログラムならLOC(行数)というように、作業時間に直接関わるものにします。  
生産性は記録時間を規模で割ったものです。単位規模あたりの作業時間ということになります。

<table>
  <tr>
    <th align="center">記録時間</th>
    <th align="center">開始　　　　　　　</th>
    <th align="center">終了　　　　　　　</th>
    <th align="center">コメント　</th>
    <th align="center">規模(頁数)</th>
    <th align="center">生産性(所要時間/頁)</th>
  </tr>
  <tr>
    <td align="center">0:26</td>
    <td align="center">2015/2/7 16:17</td>
    <td align="center">2015/2/7 16:43</td>
    <td align="center">第８章</td>
    <td align="center">9</td>
    <td align="center">0:02:53</td>
  </tr>
  <tr>
    <td align="center">0:31</td>
    <td align="center">2015/2/1 16:52</td>
    <td align="center">2015/2/1 17:23</td>
    <td align="center">第７章</td>
    <td align="center">13</td>
    <td align="center">0:02:23</td>
  </tr>
  <tr>
    <td align="center">0:34</td>
    <td align="center">2015/2/1 15:44</td>
    <td align="center">2015/2/1 16:19</td>
    <td align="center">第６章</td>
    <td align="center">14</td>
    <td align="center">0:02:26</td>
  </tr>
  <tr>
    <td align="center">0:33</td>
    <td align="center">2015/2/1 10:39</td>
    <td align="center">2015/2/1 11:12</td>
    <td align="center">第５章</td>
    <td align="center">11</td>
    <td align="center">0:03:00</td>
  </tr>
  <tr>
    <td align="center">0:27</td>
    <td align="center">2015/1/25 0:20</td>
    <td align="center">2015/1/25 0:47</td>
    <td align="center">第４章</td>
    <td align="center">11</td>
    <td align="center">0:02:27</td>
  </tr>
</table>
