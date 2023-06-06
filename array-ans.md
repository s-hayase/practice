
### 配列の数字の合計を計算して表示してみましょう

#### 表示例

`25`

#### 答え

```js
let numbers = [1, 3, 5, 7, 9];
  let sum = 0;
  for (let i = 0; i < numbers.length; i++) {
    sum = sum + numbers[i];
  }
document.write(sum);
```

### 配列にappleが何個あるか数えて表示しましょう

#### 表示例

`3`

#### 答え

```js
let words = ["apple", "banana", "orange", "apple", "grape", "apple"];
 
  let count = 0;
  for (let i = 0; i < words.length; i++) {
    if (words[i] === "apple") {
      count++;
    }
  }
document.write(count);
```
