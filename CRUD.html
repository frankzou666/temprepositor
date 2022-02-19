#bootstrap CRUD界面学习

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>table</title>
    <link rel="stylesheet" href="{{ url_for('static', filename='css/bootstrap.min.css') }}" type="text/css">
  <style>
      #booktable{
          margin: 3% auto;
      }
      #tablepart{
          margin: 10px auto;
      }
      #topbutton{
           width: 180px;
      }
      #topbutton1{
          width: 80px;
      }
      #topbutton2{
          width: 80px;
      }
  </style>


</head>
<body>
    <!-- 界面使用contrainer布器 -->
   <div id="booktable" class="container">
       <!-- 1 新增row一行，用来存放操作按纽和显录表示信息 -->
        <div class="row  justify-content-center">
	     <!-- 2 元素使用了6个col的宽度 -->
            <div class="col-6">
                {% for message in get_flashed_messages() %}
                    <div class="message-class alert alert-info">
                      {{message}}
                    <button class="close" data-dismiss="alert">&times;</button>
                    </div>
                 {% endfor %}
                <div id="topbutton">
                    <button id="topbutton1" class="btn btn-success btn-large" data-toggle="modal" data-target="#addBookModal">增加</button>
                    <a id="topbutton2" href=# class="btn btn-success btn-large">查询</a>
                </div>

            </div>
	     <!-- 2 -->
        </div>
	 <!-- 1 -->

         <!-- 4 元素使用了6个col的宽度布局表格的内容 -->
        <div id="tablepart" class="row  justify-content-center">
            <table class="col-6 table table-bordered table-hover">

                <thead>
                   <tr>
                       <td>ID</td>
                       <td>Name</td>
                       <td>Age</td>
                       <td>操作</td>
                   </tr>
                </thead>
                <tbody>
                  {% for item in data %}
                      <tr>
                       <td id="tablepartdataid">{{item[0]}}</td>
                       <td>{{item[1]}}</td>
                       <td>{{item[2]}}</td>
                       <td>
                           <a id='updateBookBtn' data-id="{{item[0]}}" class="btn btn-warning btn-small" data-toggle="modal"
                             href="#updateBookModal">修改</a>
                           <!-- 删除使用jquery事件 -->
                           <button id="deletetablebyidbtn" onclick="deletebyid({{item[0]}})" class="btn btn-danger btn-small">删除</button>

                       </td>
                      </tr>
                  {% endfor %}
                </tbody>
            </table>
        </div>
	<!-- 4  -->
   </div>
   
<!-- addModal -->
<div class="modal fade" id="addBookModal" tabindex="-1" role="dialog" aria-labelledby="addBookModalLabel" aria-hidden="true">
  <div class="modal-dialog" role="document">
    <div class="modal-content">
      <div class="modal-header">
        <h5 class="modal-title" id="addBookModalLabel">新增</h5>
        <button type="button" class="close" data-dismiss="modal" aria-label="close">
          <span aria-hidden="true">&times;</span>
        </button>
      </div>
      <div class="modal-body">
        <form class="form" method="post">
            <div class="form-group">
              <label class="form-control-label">name</label>
              <input class="form-control" type="text" name="name">
            </div>
            <div class="form-group">
              <label class="form-control-label">age</label>
              <input class="form-control" type="text" name="age">
            </div>
            <div id="modalbtn" class="justify-content-center">
              <button type="button" class="btn btn-secondary" data-dismiss="modal">关闭</button>
              <button id=type="button" type='submit' class="btn btn-primary">保存</button>
            </div>
        </form>
      </div>

    </div>
  </div>
</div>
<!-- addModal -->

<!-- updateModal -->


<div class="modal fade" id="updateBookModal" tabindex="-1" role="dialog" aria-labelledby="updateBookModalLabel" aria-hidden="true">
  <div class="modal-dialog" role="document">
    <div class="modal-content">
      <div class="modal-header">
        <h5 class="modal-title" id="updateBookModalLabel">修改</h5>
        <button type="button" class="close" data-dismiss="modal" aria-label="close">
          <span aria-hidden="true">&times;</span>
        </button>
      </div>
      <div class="modal-body">
        <form class="form" method="post">
            <div class="form-group">
              <label class="form-control-label">id</label>
              <input class="form-control updateBookModalid"  readonly="True" type="text" name="id">
            </div>
            <div class="form-group">
              <label class="form-control-label">name</label>
              <input class="form-control updateBookModalname" type="text" name="name">
            </div>
            <div class="form-group">
              <label class="form-control-label">age</label>
              <input class="form-control updateBookModalage" type="text" name="age">
            </div>
            <div id="updatemodalbtn" class="justify-content-center">
              <button type="button" class="btn btn-secondary" data-dismiss="modal">关闭</button>
              <button id="updateBookModalsaveBtn" type='submit' class="btn btn-primary">保存</button>
            </div>
        </form>
      </div>

    </div>
  </div>
</div>
<!-- updateModal -->
<script type="text/javascript" src="{{ url_for('static', filename='js/jquery.min.js') }}"></script>
<script type="text/javascript" src="{{ url_for('static', filename='js/jquery-3.2.1.slim.min.js') }}"></script>
<script type="text/javascript" src="{{ url_for('static', filename='js/bootstrap.min.js') }}"></script>
<script type="text/javascript" src="{{ url_for('static', filename='js/jquery-3.1.1.min.js') }}"></script>
<script type="text/javascript" src="{{ url_for('static', filename='js/test.js') }}"></script>
  <script>
    $(function(){
        // reload
        $("#topbutton2").click(function(){
            location.reload()
        })
        $("#updateBookModalsaveBtn").click(function(){
            location.reload()
            console.log('hel')
        })
	//事件传参，找最近的元素
        $("td>#updateBookBtn").click(function(event){
          id = $(this).closest('tr').find('td').eq(0).text();
          name = $(this).closest('tr').find('td').eq(1).text();
          age = $(this).closest('tr').find('td').eq(2).text();
          $(".updateBookModalid").val(id);
          $(".updateBookModalname").val(name);
          $(".updateBookModalage").val(age);
        })
})


function deletebyid(value){
             var url = '/auth/tab/'+value;
             $.ajax({
                 type: 'DELETE',
                 url: url,
                 success:function(result){
                     location.reload()
                 }
             })
 }
  </script>
</body>
</html>



