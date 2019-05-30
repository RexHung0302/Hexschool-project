# CSS規範

## 1.使用 SMASS

### 增加子模組
### ex. .btn .btn--primary、btn--lg

## 2.使用 OOCSS

### 結構與樣式分離
### 都會使用到的 css ex. box-shadow、display...抽離出來
### 容器內容分離
### 放到哪一個容器內都可以使用
### ex. listGroup--active 給css 搬到任何一個區塊都能使用

##3.使用 BEM 規範命名

### B -- Block (區塊) ex.clearFix
### E -- Elements (元素) __  ex. listGroup__ul
### M -- Modifire (修飾福) --  ex.listGroup--active

##4.階層限制在三層內(max:4)

##5.不使用 id (js hook 使用 js開頭命名)

### ex. js-alert

##6. 小駝峰式命名