# 第三次例会

## 概念

### 原子化css

> 原子化CSS是一种将样式表分解为单个、独立、可重用的类的技术。它的核心思想是将样式表中的每个规则都转化为一个唯一的类名，这个类名只包含一个属性和它的值。
>
> 例如，为了设置文字颜色为红色，传统的CSS规则会是这样的：
>
> ```css
> h1 {
>   color: red;
> }
> ```
>
> 使用原子化CSS的方式，可以将其转换为一个单独的类:
>
> ```css
> .red-text {
>   color: red;
> }
> ```
>
> 然后在HTML中使用该类：
>
> ```html
> <h1 class="red-text">Hello World!</h1>
> ```
>
> 原子化CSS的优点是可以提高样式表的复用性和灵活性，因为每个类都只包含一个属性和它的值，所以更容易组合和重用。同时也可以减小CSS文件的大小，因为相同的属性和值不需要多次声明。
>
> 另外，使用原子化CSS还能够方便地进行响应式设计，比如可以为不同的屏幕尺寸定义不同的类名。

### JIT

> JIT是即时编译（Just-In-Time compilation）的缩写，它是一种在程序运行时动态编译代码的技术。与传统的静态编译器不同，JIT会将代码在程序运行时实时地转换为机器码，从而可以显著提高程序的执行速度。
>
> 当程序运行到需要执行某个函数或方法的代码时，如果该函数或方法还没有被编译成机器码，JIT就会把该函数或方法的源代码编译成机器码，并且保存起来以便下次使用。这样，在下次程序执行到该函数或方法时，JIT就可以直接使用已经编译好的机器码，而不需要再次编译，从而加快了程序的执行速度。
>
> JIT被广泛应用于现代编程语言和虚拟机中，例如Java、.NET等。

### Tailwind

> Tailwind是一种基于原子化CSS的前端框架，它提供了一组预定义的类名，用于快速构建界面中的常见样式。Tailwind的核心思想是将所有可用的CSS规则都转换为单独的类名，从而使样式更易于管理和重用。
>
> 使用Tailwind可以大幅简化前端开发过程中的CSS编写工作，因为它提供了丰富的、可组合的样式类，可以轻松地创建复杂的布局和设计元素。例如，使用Tailwind可以很容易地设置颜色、字体大小、边距和背景等属性。
>
> Tailwind的另一个优点是它支持响应式设计，可以根据不同的屏幕尺寸为元素应用不同的样式，以适应不同的设备类型和分辨率。同时，Tailwind还提供了自定义配置选项，可以根据具体需求灵活调整样式和类名。
>
> 总之，Tailwind是一个功能强大的前端框架，可以帮助开发人员在快速构建界面时提高效率，并减少样式表的复杂性和冗余代码。

### PurgeCSS



### WindiCSS
