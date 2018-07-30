# swagger2pdf
- 使用swagger的json生成pdf文档(swagger.json to pdf),并解决中文乱码和显示不全问题

##使用步骤
1. 将swagger的json文件放到 swagger文件下,并命名为`swagger.json`
2. 执行maven test即可,pdf生成在target/asciidoc/pdf下
    ```bash
    mvn test
    ```