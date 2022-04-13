```

```

# README-File-Use
README文件使用技巧经验

---

1. # 文件中添加图片

   1. 使用格式

      ```html
      <img src="图片地址"/>  //显示原图,图片地址可以是项目相对地址，也可以是网络地址
      <img src="图片地址" alt="名字"/>  //显示原图,如果图片有问题，“名字”为替代显示；
      <img src="图片地址" style="zoom:50%;"/>  //缩放显示，zoom 后面的百分比为缩放比例，在编辑readme文件时可以直接在图片或链接上右键选择
      ```

      ##### 使用项目中的图片和使用网络连接各有优略，根据需要进行选择：

      - 使用项目中的图片
        - 需要上传图片，一般为方便管理需要单独创建图片文件夹
        - 给别人单发readme 文件时，在本地不能显示文件，如果是网络上（如GitHub、gitee）的项目中查看不会出现问题
        - 不怕图片链接失效
      - 使用网络图片
        - 不用上传图片，只需要找一个可靠的链接即可
        - 给别人单发readme 文件时，在本地可以正常显示文件
        - 如果图片链接失效，则不能正常显示
      - 综上，可以选择把图片上传到项目中，使用上传后的网络地址

      1. 以项目中图片的*<u>**相对地址**</u>*进行显示，

         ```html
         <img src=".\图片\10f00cfba90c332d16dfdebd7d203978.jpg" style="zoom:50%;" />
         //Markdown模式只是为了文本显示，使用时不要使用该模式，直接在readme中输入即可
         ```

         <img src=".\图片\10f00cfba90c332d16dfdebd7d203978.jpg" style="zoom:50%;" />

      2. 以项目中图片的***<u>网络地址</u>***进行显示，如有兴趣可以分析网址，在此不做分析

         ```html
         <img src="https://github.com/ChenLight-s/README-File-Use/blob/main/%E5%9B%BE%E7%89%87/fe74d29ace14cab14527450848dd3ed1.jpg?raw=true" style="zoom:50%;" />
         //Markdown模式只是为了文本显示，使用时不要使用该模式，直接在readme中输入即可
         ```

         <img src="https://github.com/ChenLight-s/README-File-Use/blob/main/%E5%9B%BE%E7%89%87/fe74d29ace14cab14527450848dd3ed1.jpg?raw=true" style="zoom:50%;" />

      3. 这里要注意，使用图片的地址时，可以直接复制图片链接![image-20220413163254303](https://github.com/ChenLight-s/README-File-Use/blob/main/%E5%9B%BE%E7%89%87/image-20220413163254303.png?raw=true)

      4. 使用网络上的图片，,如有兴趣可以分析网址，在此不做分析

         ```html
         <img src="https://gimg2.baidu.com/image_search/src=http%3A%2F%2Fimg1.doubanio.com%2Fview%2Fnote%2Fl%2Fpublic%2Fp82460877.jpg&refer=http%3A%2F%2Fimg1.doubanio.com&app=2002&size=f9999,10000&q=a80&n=0&g=0n&fmt=auto?sec=1652427813&t=e47d3ef705f8c548821a97231311e181" style="zoom:50%;" />
         //Markdown模式只是为了文本显示，使用时不要使用该模式，直接在readme中输入即可
         ```

         

      <img src="https://gimg2.baidu.com/image_search/src=http%3A%2F%2Fimg1.doubanio.com%2Fview%2Fnote%2Fl%2Fpublic%2Fp82460877.jpg&refer=http%3A%2F%2Fimg1.doubanio.com&app=2002&size=f9999,10000&q=a80&n=0&g=0n&fmt=auto?sec=1652427813&t=e47d3ef705f8c548821a97231311e181" style="zoom:50%;" />

      

      

   2. ##### 使用格式

      ```html
      
      ![](图片地址)   
      其中 ！ [] ()  均为英文字符；
      ! 为图片显示的头；
      []内可以写任意字符，其中的内容是图片不能正常显示时替代显示的文字；
      () 为图片路径;
      可以是项目内图片的地址，*<u>注意使用相对项目的地址目录层级要用 "/" ,使用 "\"虽然在readme 本地文件能显示，但在git上均不能显示。
      也可以是网络路径，网络地址直接复制就行，*<u>**其目录层级用的是 "\";
      <!--readme文件中在图片或连接上右键可以缩放图片调整大小，但是调整完大小后，其格式自动变成了格式 1,也就是该模式不能进行图片缩放-->
      ```

      1. ###### 以项目中图片的*<u>**相对地址**</u>*进行显示，例如该项目中，要显示 图片/10f00cfba90c332d16dfdebd7d203978.jpg  ，只需要输入 ：

         ```
         ![](./图片/10f00cfba90c332d16dfdebd7d203978.jpg) //Markdown模式只是为了文本显示，使用时不要使用该模式，直接在readme中输入即可
         ```

         ![](./图片/10f00cfba90c332d16dfdebd7d203978.jpg)

      2. 以项目中图片的*<u>**网络地址**</u>*进行显示，例如该项目中，,如有兴趣可以分析网址，在此不做分析

         ```
         ![](https://github.com/ChenLight-s/README-File-Use/blob/main/%E5%9B%BE%E7%89%87/e72bc48116d2db6e3ce4801f8e5ff2e0.jpg?raw=true) //Markdown模式只是为了文本显示，使用时不要使用该模式，直接在readme中输入即可
         ```

         ![](https://github.com/ChenLight-s/README-File-Use/blob/main/%E5%9B%BE%E7%89%87/e72bc48116d2db6e3ce4801f8e5ff2e0.jpg?raw=true)

   2. ###### 使用网络地址,如有兴趣可以分析网址，在此不做分析

      1. 例如，github上的图片
      
         ```
          ![](https://raw.githubusercontent.com/ChenLight-s/ChenLight-s.github.io/master/图片/罗小黑战记.png)
          //Markdown模式只是为了文本显示，使用时不要使用该模式，直接在readme中输入即可
         ```
      
         
      
          ![](https://raw.githubusercontent.com/ChenLight-s/ChenLight-s.github.io/master/图片/罗小黑战记.png)
      
      2. 网络上的图片
      
         ```
         ![](http://tva3.sinaimg.cn/large/ae07c035gy1gqk6zlt4r8j20n00n0whe.jpg)
         //Markdown模式只是为了文本显示，使用时不要使用该模式，直接在readme中输入即可
         ```
      
         ![](http://tva3.sinaimg.cn/large/ae07c035gy1gqk6zlt4r8j20n00n0whe.jpg)

   ##### 
