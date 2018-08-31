
//下面的是get请求


//获取所有用户信息
http://localhost:3000/users
//获取id为1的用户信息
http://localhost:3000/users/1
//获取公司的所有信息
http://localhost:3000/companies
//获取单个公司的信息
http://localhost:3000/companies/1
//获取所有公司id为3的用户
http://localhost:3000/companies/3/users
//根据公司名字获取信息
http://localhost:3000/companies?name=Google
//根据多个名字获取公司信息
http://localhost:3000/companies?name=Google&name=Apple
//获取一页中只有两条数据
http://localhost:3000/companies?_page=1&_limit=2
//升序排序  desc降序  asc升序
http://localhost:3000/companies?_sort=name&_order=asc
//获取年龄为30以及30以上的
http://localhost:3000/users?age_gte=30
//获取年龄为30到40之间的
http://localhost:3000/users?age_gte=30&age_gte=40
//搜索用户信息
http://localhost:3000/users?q=d


//post请求需要借助postman
//header 和 Body需要设置 content-type:application/json   Body要post的数据
//delete 借助postman直接删除即可
//patch  更新  借助postman


//把jsonplaceholder 中的数据拿到我们的本地来


//在本地中拿到jsonplaceholder中的数据  在json-server中找到Remote schema
