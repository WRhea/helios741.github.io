��96��֮ǰ����˵�İ�`window`����`document`����ı������ص��˱հ����棬�����ĺô�һ��**���ڽ��д���ѹ��**����**����֮�����˷�����д**��
�ӵ�100�п�ʼ��`init`����Ҳ�������ǳ��õ�`$("")`�����������ȿ������һ��`jQuery`��䣺
`$("li").css("color","red")`
��仰����˼��ѡ��ҳ����`li`Ȼ����������ɫ��Ϊ��ɫ���������ʹ��ԭ��`javascript`��������ķ�ʽ������д��
```javascript
var div  = document.getElementsByTagName("li");
for(var i=0,len = div.length;i<len;i++){
    div[i].style.background = "red";
}
```
��ʼ����д�ǵȼ۵ġ�
����ʹ��`$("")`��ʱ���޷Ǿ�����ļ��ַ�ʽ��
1. $("div") , $(".na") ,  $("div ul")
2. $("#box")
3. $("<li>") $("<li>a</li><li>b</li>")
4. $(this) , $(document)