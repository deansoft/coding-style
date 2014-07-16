# Java Coding Style

## 格式

### 縮排

以四個空白當作縮排的單位，不要使用 Tab

### if/if-else/if else-if else 陳述 (statement)

if-else 相關的陳述，應以下列方式寫成:

    if (condition) {
        statements;
    }

    if (condition) {
        statements;
    } else {
        statements;
    }

    if (condition) {
        statements;
    } else if (condition) {
        statements;
    } else {
        statements;
    }

請不要在 if-else 中省略 {}，以免造成[非預期的錯誤](https://www.imperialviolet.org/2014/02/22/applebug.html)。不建議寫成如下的方式:

    if (condition)
        statements;

### 修飾子 (Modifier)

若使用到類別或成員變數方法的修飾子，應依照下列的順序來使用

    public protected private abstract static final transient volatile synchronized native strictfp

## 命名

### 類別名稱 (Class name)

類別的名稱以 UpperCamelCase 的方式寫成

類別名稱應盡量以名詞或名詞片語來命名，如 Character 或 ImmutableList

### 方法名稱 (Method name)

方法名稱以 lowerCamelCase 的方式寫成

方法名稱應盡量以動詞或動詞片語來命名，如 sendMessage 或 stop

### 常數名稱 (Constant name)

常數名稱以 CONSTANT_CASE 的方式寫成，全部使用大寫字母，每個字之間以底線連接
