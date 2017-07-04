# hello-word
practice
<!--生成数据列表-->
    <script type="text/template" id="goodsListBox">
        {{each result as obj index}}
            <li>
                <a href="discount.html?productid={{obj.productId}}">
                    <div class="imgContainer">{{#obj.productImg}}</div>
                    <p>{{obj.productName}}</p>
                    <p>{{obj.productPrice}}</p>
                    <div class="info">
                        {{obj.productFrom}} | {{obj.productTime}}
                    </div>
                </a>
            </li>
        {{/each}}
    </script>
