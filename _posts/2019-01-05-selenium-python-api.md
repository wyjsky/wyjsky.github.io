Selenium Python API
==========
***********************

###WebDriver操纵浏览器
1.获取当前页面的url地址:  
driver.current_url

2.获取当前窗口的句柄:  
driver.current\_window\_handle

3.获取该实例底层浏览器名称:  
driver.name

4.获取当前页面源代码:  
driver.page_source

5.获取当前页面的标题:  
driver.title

6.获取当前session里所有窗口的句柄:  
driver.window_handles

###WebDriver与浏览器窗口、网页和页面元素交互

1.回退到之前打开的页面:  
driver.back()

2.前进到回退之前的页面:   
driver.forward()

3.关闭当前浏览器窗口:  
driver.close()

4.退出当前driver并关闭所有相关窗口:  
driver.quit()

5.访问目标URL并加载网页到当前的浏览器会话:  
driver.get('http://www.baidu.com')

6.最大化当前浏览器窗口:  
driver.maximize_window()

7.设置浏览器窗口大小:  
driver.set_window_size(800,600)

8.刷新当前页面:  
driver.refresh()

9.返回当前页面唯一焦点所在的元素或者元素体:  
driver.switch\_to\_active\_element()

10.把焦点切换至当前页面弹出的警告:  
driver.switch\_to\_alert()

11.切换焦点至默认框架内:  
driver.switch\_to\_default\_content()

12.通过索引、名称和网页元素将焦点切换到指定的框架:  
driver.switch_to_frame('frame_reference')

13.切换焦点到指定的窗口:  
driver.switch_to_window('main')

14.超时设置等待目标元素被找到:  
driver.implicitly\_wait(30)

15.设置一个页面完全加载完成的超时等待时间:  
driver.set_page_load_timeout(30)

16.设置脚本执行的超时时间:  
driver.set_script_timeout(30)



