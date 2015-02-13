# fyCountDown

##功能
倒计时插件

##参数释义
* countdownSeconds:20,     //默认倒数20秒
* alwaysShown:'',          //默认如果最大单位变为0后不再显示
* addZero:true,            //默认如果数字为个位数，会在前边加0
* onlySeconds:false,       //默认不只是倒计时秒数。true时只倒计时秒数，不分其他单位
* notySeconds:10,          //默认倒计时提醒为10秒,到10秒后给div加上class=notifing
* notyClass:'notifing',    //默认倒计时提醒class为notifing
* unit:{                   //默认倒计时单位文字为天，时，分，秒
    d:'天',
    h:'时',
    m:'分',
    s:'秒'
  },
* onFinish:function(){}    //默认倒计时完成后回调为空


##调用示例
```
<script src="http://libs.baidu.com/jquery/2.0.0/jquery.min.js"></script>
<script src="jquery.fyCountDown-1.0.js"></script>
<script>
  $('#count-down1').fyCountDown({
    countdownSeconds: 65,
    addZero:true,
    notySeconds:60,
    notyClass:'notifing',
    onFinish: function(){
      //
    }
  });
</script>
```
更多实例见demo
