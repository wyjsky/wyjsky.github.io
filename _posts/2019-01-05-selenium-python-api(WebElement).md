Selenium Python API(WebElement)
==========
***********************  


### WebElement功能  

1.获取元素大小:  
element.size

2.获取元素的HTML标签名称:  
element.tag_name

3.获取元素的文本值:  
element.text

### WebElement方法  

1.清楚文本框或者文本域中的内容:  
element.clear()

2.单击元素:  
element.click()

3.获取元素的属性值:  
element.get_attribute("maxlength")

4.检查元素对于用户是否可见:  
element.is_displayed()

5.检查元素是否可用:  
element.is_enabled()

6.检查元素是否被选中:  
element.is_selected()

7.模拟输入文本:  
element.send_keys("foo")

8.用于提交表单:  
element.submit()

9.获取css属性的值:  
element.value_of_css_property("backgroundcolor")