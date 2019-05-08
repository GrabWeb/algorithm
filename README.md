# resume
exercise
使用JS添加HTML，并实现键盘功能
//取出 localStorage 中的 zzz 对应的 hash
         var hashInLocalStorage = JSON.parse(localStorage.getItem('zzz') || 'null')
         if(hashInLocalStorage){
             hash = hashInLocalStorage //保证hash优先取之前用户设置的
         } 
         localStorage.setItem('zzz', JSON.stringify(hash))//使用localStorage储存，解决属性消失问题
