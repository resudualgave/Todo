# Todo

参考内容：http://weibo.com/ttarticle/p/show?id=2309614093213819410478

本想实现重复任务无法建立，可是没能成功
          if(tasks == null){
         for (var i=0;i<tasks.length;i++){ 
           if(task.title == tasks[i].title){
             exist = 1;
             break;
           }
         }
        }
