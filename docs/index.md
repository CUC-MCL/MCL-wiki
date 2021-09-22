# MCL大学生学术训练季简介
MCL（Most Creative Learning）大学生学术训练季旨在对我校理工科本科生进行基本的学术训练，熟悉学术研究的基本流程和方法，为今后从事学术研究打下良好的基础。训练季从看顶刊、读顶会开始，同学们在此过程中将及时组建自身所需的知识体系，洞察学术前沿方向，掌握科研的基本方法和实验数据分析技能，并能在此基础上提升自己的学术写作能力和创新能力。
历经8个月的首届MCL大学生学术训练季已顺利结束。自2021年5月底开始，将启动为期10个月的第二届MCL大学生学术训练季，为学生提供更多学术训练机会，让更多同学从中受益。





## 更换主题的主色

<div id="color-button">
<button data-md-color-primary="red">Red</button>
<button data-md-color-primary="pink">Pink</button>
<button data-md-color-primary="purple">Purple</button>
<button data-md-color-primary="deep-purple">Deep Purple</button>
<button data-md-color-primary="indigo">Indigo</button>
<button data-md-color-primary="blue">Blue</button>
<button data-md-color-primary="light-blue">Light Blue</button>
<button data-md-color-primary="cyan">Cyan</button>
<button data-md-color-primary="teal">Teal</button>
<button data-md-color-primary="green">Green</button>
<button data-md-color-primary="light-green">Light Green</button>
<button data-md-color-primary="lime">Lime</button>
<button data-md-color-primary="yellow">Yellow</button>
<button data-md-color-primary="amber">Amber</button>
<button data-md-color-primary="orange">Orange</button>
<button data-md-color-primary="deep-orange">Deep Orange</button>
<button data-md-color-primary="brown">Brown</button>
<button data-md-color-primary="grey">Grey</button>
<button data-md-color-primary="blue-grey">Blue Grey</button>
<button data-md-color-primary="white">White</button>
</div>

<script>
  var buttons = document.querySelectorAll("button[data-md-color-primary]");
  Array.prototype.forEach.call(buttons, function(button) {
    button.addEventListener("click", function() {
      document.body.dataset.mdColorPrimary = this.dataset.mdColorPrimary;
      localStorage.setItem("data-md-color-primary",this.dataset.mdColorPrimary);
    })
  })
</script>