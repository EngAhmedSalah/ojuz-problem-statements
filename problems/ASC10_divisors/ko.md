우리 모두 10진법이 뭔지 잘 알고 있습니다. 역사가들은 10진법이 등장한 이유는 사람의 손가락이 10개이기 때문이라고 합니다. 그들이 맞을 수도 있습니다. 하지만 10진법은 종종 편하지 않을 때가 있습니다. 10의 약수가 1, 2, 5, 10으로 4개밖에 없기 때문입니다. 따라서, $1/3$, $1/4$, $1/6$과 같은 분수들을 10진법으로 표현하면 매우 불편합니다. 이 상황에서 12진법, 24진법, 심지어 60진법은 10진법보다 훨씬 편리할 겁니다.

이 진법들이 편리한 이유는 약수의 개수가 10보다 많기 때문입니다. 12의 약수는 6개, 24의 약수는 8개, 60의 약수는 12개나 됩니다. 여기서 승현이는 $n$을 넘지 않는 자연수들 중에서 약수의 개수가 가장 많은 자연수를 찾고자 합니다. 여러분은 이걸 찾는 프로그램을 작성해야 합니다.

### 입력 형식

$n$이 주어집니다. ($1 \le n \le 10^{16}$)

### 출력 형식

첫 번째 줄에 $n$ 이하의 자연수들 중 약수의 개수가 가장 많은 수를 출력합니다. 이러한 경우가 여러 개 있다면, 가장 작은 수를 출력합니다.

### 예제

<table class='table table-bordered table-condensed'>
 <thead>
  <tr>
   <th style="width: 50%;">입력</th>
   <th style="width: 50%;">출력</th>
  </tr>
 </thead>
 <tbody>
  <tr>
   <td class="code-font">10</td>
   <td class="code-font">6</td>
  </tr>
  <tr>
   <td class="code-font">20</td>
   <td class="code-font">12</td>
  </tr>
  <tr>
   <td class="code-font">100</td>
   <td class="code-font">60</td>
  </tr>
 </tbody>
</table>