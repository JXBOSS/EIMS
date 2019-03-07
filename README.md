# Vue+ElementUI数据库管理系统

#### 使用Vue和Element对mysql数据库进行创作和管理操作

### 页面地址：[http://jiaxiong.xyz:8080/index.html](http://jiaxiong.xyz:8080/index.html)

### 页面操作：

<table>
    <thead>
        <tr>
            <th>名称</th>
            <th>类型</th>
            <th>说明</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>添加员工</td>
            <td>username,password...</td>
            <td>输入信息,<注册>账户</td>
        </tr>
         <tr>
            <td>管理员工</td>
            <td>username,password...</td>
            <td>查看信息,<编辑>账户</td>
        </tr>
        <tr>
            <td>删除员工</td>
            <td>delete,click</td>
            <td><删除>员工数据</td>
        </tr>
    </tbody>
</table>

### 数据请求参数接口及示例：

#### 成功返回值：success

<table>
	<thead>
		<tr>
			<th>名称</th>
			<th>接口名称</th>
			<th>url接口示例</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<td>查询</td>
			<td>/getData</td>
			<td>http://127.0.0.1:8080/getData</td>
		</tr>
		<tr>
			<td>增加</td>
			<td>/addData</td>
			<td>http://127.0.0.1:8080/addData</td>
		</tr>
		<tr>
			<td>编辑</td>
			<td>/editData</td>
			<td>http://127.0.0.1:8080/editData</td>
		</tr>
		<tr>
			<td>删除</td>
			<td>/deleteData</td>
			<td>http://127.0.0.1:8080/deleteData</td>
		</tr>
	</tbody>
</table>

###  数据返回参数说明：

####  返回格式：json

<table>
	<thead>
		<tr>
			<th>名称</th>
			<th>类型</th>
			<th>说明</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<td>ID</td>
			<td>int</td>
			<td>数据的唯一标示</td>
		</tr>
		<tr>
			<td>name</td>
			<td>String</td>
			<td>员工姓名</td>
		</tr>
		<tr>
			<td>sex</td>
			<td>Boolean（int）</td>
			<td>员工姓别：男（1）,女（0）</td>
		</tr>
		<tr>
			<td>birthday</td>
			<td>date</td>
			<td>出生年月日</td>
		</tr>
		<tr>
			<td>IDCard</td>
			<td>number</td>
			<td>身份证号码</td>
		</tr>
		<tr>
			<td>status</td>
			<td>Boolean（int）</td>
			<td>在职（1）或离职（0）</td>
		</tr>
		<tr>
			<td>joinDate</td>
			<td>date</td>
			<td>入职时间</td>
		</tr>
		<tr>
			<td>leaveDate</td>
			<td>date</td>
			<td>离职时间</td>
		</tr>
		<tr>
			<td>number</td>
			<td>int</td>
			<td>员工电话号码</td>
		</tr>
		<tr>
			<td>salary</td>
			<td>int</td>
			<td>员工薪资</td>
		</tr>
		<tr>
			<td>department</td>
			<td>String</td>
			<td>员工职位</td>
		</tr>
	</tbody>
</table>