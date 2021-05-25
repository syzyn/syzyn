- 👋 Hi, I’m @syzyn
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
syzyn/syzyn is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
111  
hi

<body>
    <div id="app1">app1:{{title}}</div>
    <div id="app2">app2:{{title}}</div>
    <script>
    var Vue2=Vue.extend({
        data(){
            return{title:'hello'}
        }
    })
    var vm1=new Vue({el:'#app1'})
    var vm2=new Vue2({el:'#app2'})
    </script>
</body>
</html>
