---
id: 5e9a093a74c4063ca6f7c154
title: 'Numpy: Масиви'
challengeType: 11
videoId: VDYVFHBL1AM
bilibiliIds:
  aid: 890607366
  bvid: BV1zP4y1h7FR
  cid: 409011400
dashedName: numpy-arrays
---

# --description--

*Замість використаного у відеоматеріалі notebooks.ai можна користуватись блокнотом Google Colab.*

Додаткові ресурси:

-   [Блокноти на GitHub](https://github.com/ine-rmotr-curriculum/freecodecamp-intro-to-numpy)
-   [Як відкрити блокноти з GitHub використовуючи Google Colab.](https://colab.research.google.com/github/googlecolab/colabtools/blob/master/notebooks/colab-github-demo.ipynb)

# --question--

## --text--

Який результат буде виведено на екран після виконання наведеного нижче коду?

```py
A = np.array([
    ['a', 'b', 'c'],
    ['d', 'e', 'f'],
    ['g', 'h', 'i']
])

print(A[:, :2])
```

## --answers--

```py
[['a' 'b']]
```

---

```py
[['b' 'c']
['e' 'f']
['h' 'i']]
```

---

```py
[['a' 'b']
['d' 'e']
['g' 'h']]
```

## --video-solution--

3
