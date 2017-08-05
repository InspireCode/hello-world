== 性质 ==

''C''<sub>''n''</sub>的另一个表达形式为<math>C_n = {2n\choose n} - {2n\choose n+1} \quad\mbox{ for }n\ge 1</math>
所以，''C''<sub>''n''</sub>是一个[[自然数]]；这一点在先前的通项公式中并不显而易见。这个表达形式也是André对前一公式证明的基础。（见下文的[[第二个证明]]。）

[[递推关系]]
:<math>C_0 = 1 \quad \mbox{and} \quad C_{n+1}=\sum_{i=0}^{n}C_i\,C_{n-i}\quad\mbox{for }n\ge 0.</math>

它也满足
:<math>C_0 = 1 \quad \mbox{and} \quad C_{n+1}=\frac{2(2n+1)}{n+2}C_n,</math>
这提供了一个更快速的方法来计算卡塔兰数。

卡塔兰数的渐近增长为
:<math>C_n \sim \frac{4^n}{n^{3/2}\sqrt{\pi}}</math>
它的含义是当''n''&nbsp;→&nbsp;∞时，左式除以右式的商[[极限|趋向于]]1。（这可以用''n''!的[[斯特灵公式]]来证明。）

所有的奇卡塔兰数''C''<sub>''n''</sub>都满足<math>n=2^k-1</math>。所有其他的卡塔兰数都是偶数。
