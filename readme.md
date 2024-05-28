В этом примере мы убрали **"одну обвертку"** div. В таком случае первый элемент _(child-one child)_ при прокрутке будет исчезать, его заменяет второй _(child-two child)_ и далее третий _(child-three child)_ заменяет второй. Третий элемент прилипает и также далее исчезает.

```<body>
  <div class="parent">
    Parent
    <!-- <div> -->
    <div class="child-one child">One</div>
    <ul>
      <li>Lorem, ipsum dolor.</li>
      <li>Lorem, ipsum dolor.</li>
      <li>Lorem, ipsum dolor.</li>
    </ul>
    <!-- </div> -->
    <!-- <div> -->
    <div class="child-two child">Two</div>
    <ul>
      <li>Lorem, ipsum dolor.</li>
      <li>Lorem, ipsum dolor.</li>
      <li>Lorem, ipsum dolor.</li>
    </ul>
    <!-- </div> -->
    <!-- <div> -->
    <div class="child-three child">Three</div>
    <ul>
      <li>Lorem, ipsum dolor.</li>
      <li>Lorem, ipsum dolor.</li>
      <li>Lorem, ipsum dolor.</li>
    </ul>
    <!-- </div> -->
  </div>
</body>
```

![without_div](/img/without%20div.png)

---

Вариант когда мы **раскоментировали div** будет без наслаивания и при прокрутке один элемент становится под другим

![without_div](/img/with%20div.png)
