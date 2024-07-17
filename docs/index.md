# 欢迎来到尘心的truism

尘心（chenxin）网名已存，故取名心尘大海（[xinchen-sea](https://github.com/xinchen-sea)）<br>
看到了很多大佬都在使用这种mkdocs for material形式的笔记本（[鹤翔万里的个人笔记本](https://note.tonycrane.cc/)、[SAVIA的外装大脑](https://savia7582.github.io/Exterior/)、[PhilFan的笔记本](https://www.philfan.cn/)...）,我很心动，故学之，努力打造属于自己mkdocs<br>
本网页用于记录笔者的包括但不限于笔记和心得<br>
说的都是老生常谈，故曰truism（也可以翻译成“真理”/doge）<br>
如果你觉得我的truism（陈词滥调）对你有用的话，不妨动动小手点一个star！<br>


!!! note "可能会有的东西"
    施工中......<br>



primary用于标题、侧边栏、文本链接和其他几个组件。单击图块以更改primary：       
浅色(default)模式下默认颜色：`indigo`；深色模式下默认颜色：`black`

!!! tip "快来试试吧"
    <div class="mdx-switch">
      <button data-md-color-primary="red"><code>red</code></button>
      <button data-md-color-primary="pink"><code>pink</code></button>
      <button data-md-color-primary="purple"><code>purple</code></button>
      <button data-md-color-primary="deep-purple"><code>deep purple</code></button>
      <button data-md-color-primary="indigo"><code>indigo</code></button>
      <button data-md-color-primary="blue"><code>blue</code></button>
      <button data-md-color-primary="light-blue"><code>light blue</code></button>
      <button data-md-color-primary="cyan"><code>cyan</code></button>
      <button data-md-color-primary="teal"><code>teal</code></button>
      <button data-md-color-primary="green"><code>green</code></button>
      <button data-md-color-primary="light-green"><code>light green</code></button>
      <button data-md-color-primary="lime"><code>lime</code></button>
      <button data-md-color-primary="yellow"><code>yellow</code></button>
      <button data-md-color-primary="amber"><code>amber</code></button>
      <button data-md-color-primary="orange"><code>orange</code></button>
      <button data-md-color-primary="deep-orange"><code>deep orange</code></button>
      <button data-md-color-primary="brown"><code>brown</code></button>
      <button data-md-color-primary="grey"><code>grey</code></button>
      <button data-md-color-primary="blue-grey"><code>blue grey</code></button>
      <button data-md-color-primary="black"><code>black</code></button>
      <button data-md-color-primary="white"><code>white</code></button>
    </div>
    <script>
      var buttons = document.querySelectorAll("button[data-md-color-primary]")
      buttons.forEach(function(button) {
      button.addEventListener("click", function() {
          var attr = this.getAttribute("data-md-color-primary")
          document.body.setAttribute("data-md-color-primary", attr)
          var name = document.querySelector("#__code_1 code span.l")
          name.textContent = attr.replace("-", " ")
        })
      })
    </script>
